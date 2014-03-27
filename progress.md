toolbeltをインストールしたけど、以下のエラーでheroku openが失敗する。
Opening ancient-waters-9458... failed
 !    Heroku client internal error.
 !    Search for help at: https://help.heroku.com
 !    Or report a bug at: https://github.com/heroku/heroku/issues/new

    Error:       uninitialized constant Heroku::Command::RestClient (NameError)
    Backtrace:   /usr/local/heroku/lib/heroku/command.rb:225:in `rescue in run'
                 /usr/local/heroku/lib/heroku/command.rb:269:in `run'
                 /usr/local/heroku/lib/heroku/cli.rb:28:in `start'
                 /usr/local/heroku/bin/heroku:24:in `<main>'

    Command:     heroku open
    Version:     heroku-toolbelt/3.6.0 (x86_64-linux) ruby/1.9.3

心が折れたので次に進んでしまおう。

2.3.3までやった。