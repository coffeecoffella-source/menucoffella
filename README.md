# Coffella — меню (GitHub Pages)

Готово к публикации на GitHub Pages.

## Структура
```
/
├─ index.html
└─ assets/
   └─ Logotype.svg   ← замените на ваш настоящий логотип (тем же именем)
```

## Публикация
1. Создайте репозиторий (например, `coffella-menu`) и загрузите эти файлы.
2. В Settings → Pages:
   - Source: **Deploy from a branch**
   - Branch: **main** (или master) и папка **/(root)**
3. Сохраните. Через минуту сайт будет по адресу вида:
   `https://<ваш-юзер>.github.io/coffella-menu/`

## Замена логотипа
- Просто замените `assets/Logotype.svg` своим файлом с таким же именем.
- Высота в шапке управляется CSS-классом `.logo-img` (по умолчанию 56px).
