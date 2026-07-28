# Figma rules для слайдов Чижика

## Формат

- Основной фрейм: `1920 × 1080`.
- Все текстовые элементы — редактируемый `TEXT`.
- Fact не переводить в кривые.
- SVG-графики импортировать так, чтобы текст оставался текстом.

## Шрифты

Использовать семейство `Fact`:
- `Compressed Extra Bold`
- `Compressed Bold`
- `Condensed Extra Bold`
- `Condensed Bold`
- `Condensed Medium`
- `Medium`
- `Bold`

Если Fact недоступен в Figma, сначала загрузить шрифты в аккаунт/организацию Figma. Не использовать случайный fallback.

## Слои

Рекомендуемая структура:
- `BG`
- `TYPE / headline`
- `TYPE / captions`
- `DATA / charts`
- `3D / mascot`
- `3D / retail objects`
- `MARKER / pink notes`
- `TEXTURE / grain`
- `QA / reference` — только вне финального фрейма

## Экспорт

- Для презентации: PNG 1920×1080.
- Для редактируемых графиков: SVG с текстом.
- Для сложных 3D/маскота: PNG с прозрачным фоном.
