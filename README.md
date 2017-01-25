# Slime Sublime/TextMate Bundle

This is the [Sublime Text](http://www.sublimetext.com/)/[Textmate](http://macromates.com/) bundle for [Slime](http://slime-lang.com/), based on the [Ruby Slim bundle](https://github.com/slim-template/ruby-slim.tmbundle), which is based on the [Handcrafted Haml bundle](http://github.com/handcrafted/handcrafted-haml-textmate-bundle).

## Installation (Sublime Text)
Install it via [Package Control](https://packagecontrol.io/packages/Slime). Package name is `Slime`.

## TextMate

My primary editor is Sublime Text, so unfortunately I can't check all Text Mate's features.
If you run into any issues, just tell me and I'll try to fix them.

## Troubleshooting

- **Autocomplete popup doesn't appear for snippets in Sublime Text**

    You might want to add this line to your config (either syntax specific or system wide):

    ```json
    "auto_complete_selector": "source, text"
    ```

    [Details](http://stackoverflow.com/questions/12656448/sublime-text-2-auto-completion-popup-does-not-work-properly).