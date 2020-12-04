# Supporting multiple image file types in HTML

AVIF, WEBP, [JPEG2000](https://davidwalsh.name/how-to-use-jpeg-2000-jp2-for-a-faster-images-on-iphone), JPG

Example images generated with [Squoosh.app](https://squoosh.app/)

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
