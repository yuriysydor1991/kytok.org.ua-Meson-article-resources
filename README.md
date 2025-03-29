# kytok.org.ua-Meson-article-resources

Демонстраційний Meson проект для легкого старту. 

Стаття для проекту за посиланням [http://kytok.org.ua/post/systema-zbyrannya-prohram-meson-lehkyj-start](http://kytok.org.ua/post/systema-zbyrannya-prohram-meson-lehkyj-start)

# Клонування і побудова

Щоб склонувати і побудувати проект необхідно виконати наступні команди (Unix-подібні):

```
git clone https://github.com/yuriysydor1991/kytok.org.ua-Meson-article-resources.git

cd kytok.org.ua-Meson-article-resources

meson setup builddir && meson compile -C builddir
```

Після чого побудований артефакт можна знайти за шляхом `./builddir/TheMesonEasyStarterDemoProject`
