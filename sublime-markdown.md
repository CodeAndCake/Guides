# Markdown in Sublime Text

[Install Markdown Preview](https://github.com/revolunet/sublimetext-markdown-preview#installation-)

Change preferences

	...
    "skip_default_stylesheet": true,
    ...
    "html_simple": true,
    ...
    "embed_css_for_sublime_output": false


Add this shortcut to quickly convert MD to HTML

    { 
		"keys": ["alt+m"], 
		"command": "markdown_preview", 
		"args": {"target":"sublime", "parser":"github"} 
	}