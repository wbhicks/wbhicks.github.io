# {{$.Title}}Z

{{- /* trim (readFile .Content) "\n" | safeHTML 

{{ $allText | safeHTML }}
*/ -}}

{{ $allText := .Content }}

{{ $allText = replaceRE `<p>` `

` $allText }}

{{ $allText = replaceRE `</p>` `

` $allText }}

{{ $allText = replaceRE `<h2 id=[^>]+>(.+)</h2>` `## $1 ` $allText }}
{{ $allText = replaceRE `<h3 id=[^>]+>(.+)</h3>` `### $1 ` $allText }}
{{ $allText = replaceRE `<h4 id=[^>]+>(.+)</h4>` `#### $1 ` $allText }}

{{ $allText = replaceRE 
    `↗ <a href="([^"]+)">(.+)</a> \(external\)`
    `=> $1 $2 (external link)`
    $allText
}}

{{ $allText }}
