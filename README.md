# Supporting multiple image file types in HTML

AVIF, WEBP, JPEG2000, JPG

## Sample code

```html
<picture>
	<source type="image/avif" srcset="image.avif" /><!-- Chrome -->
	<source type="image/webp" srcset="image.webp" /><!-- new Safari, Firefox, old Chrome -->
	<source type="image/jp2" srcset="image.jp2" /><!-- old Safari -->

	<img src="image.jpg" alt="" />
</picture>
```

## Styling

[Styling `<picture>` with CSS](https://stackoverflow.com/a/25398890)
