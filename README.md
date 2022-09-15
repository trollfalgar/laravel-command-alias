# Laravel Command Alias
A set of alias for the most utilized commands in the Laravel ecosystem.

- Paste the list below inside the `.bashrc` placed in your *Home* directory.
- After saving the file, run the command `source ~/.bashrc`.
- Done!


# Personalized Alias For Laravel, Sail & Composer
alias sail='[ -f sail ] && bash sail || bash vendor/bin/sail'
\
alias pint='vendor/bin/pint'
\
alias pa='php artisan'
\
alias sa='sail artisan'
\
alias c='composer'
\
alias sc='sail composer'
\
alias cu='composer update'
\
alias scu='sail composer update'
\
alias cr='composer require'
\
alias scr='sail composer require'
\
alias csu='sudo composer self-update'
\
alias scsu='sail composer self-update'
\
alias ni='npm install'
\
alias nu='npm update'
\
alias sni='sail npm install'
\
alias snu='sail npm update'
\
alias dev='npm run dev'
\
alias watch='npm run watch' `#if you use Laravel Mix`
\
alias prod='npm run prod' `#if you use Laravel Mix`
\
alias build='npm run build' `#if you use Vite`
\
alias sdev='sail npm run dev'
\
alias swatch='sail npm run watch' `#if you use Laravel Mix`
\
alias sprod='sail npm run prod' `#if you use Laravel Mix`
\
alias sbuild='sail npm run build' `#if you use Vite`