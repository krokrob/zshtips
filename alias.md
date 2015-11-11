If you want to add some smart aliases to your terminal boring commands :smile:

Open .zshrc file in SublimeText:
`stt ~/.zshrc`

Then insert your own aliases:
```
# Gather handy aliases
[[ -f "$HOME/.aliases" ]] && source "$HOME/.aliases"
alias bi="bundle install"
alias migdev="heroku run rake db:migrate --app your_staging_app_name"
alias pushhk="git push heroku master"
```
