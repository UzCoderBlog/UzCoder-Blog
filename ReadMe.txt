Ссылка на demo
https://dev.stack.jimmycai.com
https://demo.stack.jimmycai.com

-------------------------------------------------
WiKi
https://stack.jimmycai.com/config/widgets#widgets
https://themes.gohugo.io/themes/hugo-theme-stack/


-------------------------------------------------
Submodle:

1.Проверьте наличие подмодуля: Выполните команду, чтобы посмотреть, есть ли уже добавленный подмодуль:

git submodule

Если hugo-theme-stack уже добавлен как подмодуль, вам может не понадобиться добавлять его снова.

2.Удалите существующий подмодуль (если он не нужен): Если подмодуль уже добавлен и вы хотите его удалить, выполните следующие команды:

git submodule deinit -f themes/hugo-theme-stack
git rm -f themes/hugo-theme-stack
git commit -m "Remove existing submodule"

git submodule add https://github.com/CaiJimmy/hugo-theme-stack.git themes/hugo-theme-stack 

3.Добавьте подмодуль снова: После удаления подмодуля вы можете повторно добавить его:

git submodule add https://github.com/CaiJimmy/hugo-theme-stack.git themes/hugo-theme-stack

Если hugo-theme-stack существует как обычная папка, и вы хотите ее заменить подмодулем, сначала удалите эту папку:

rm -rf themes/hugo-theme-stack

-------------------------------------------------
Мои репозитории:
https://github.com/UzCoderBlog/UzCoder-Blog.git

echo "# UzCoder-Blog" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/uzcoderblog/uzcoderblog.github.io.git
git push -u origin main

git remote add origin https://github.com/uzcoderblog/uzcoderblog.github.io.git
git branch -M main
git push -u origin main

