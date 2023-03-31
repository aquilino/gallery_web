# Aquí está el código HTML y CSS para crear una galería de imágenes básica en HTML5 y CSS:

## HTML:
```html
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Galería de Imágenes</title>
	<link rel="stylesheet" href="style.css">
</head>
<body>
	<div class="gallery">
		<img src="image/image1.jpg" alt="Imagen 1">
		<img src="image/image2.jpg" alt="Imagen 2">
		<img src="image/image3.jpg" alt="Imagen 3">
		<img src="image/image4.jpg" alt="Imagen 4">
		<img src="image/image5.jpg" alt="Imagen 5">
		<img src="image/image6.jpg" alt="Imagen 6">
		<img src="image/image7.jpg" alt="Imagen 7">
		<img src="image/image8.jpg" alt="Imagen 8">
	</div>

	<div class="contact-button">
		<a href="/contacto">Contáctanos</a>
	</div>
</body>
</html>
```

## CSS:
```css
.gallery {
	display: grid;
	grid-template-columns: repeat(4, 1fr);
	grid-gap: 10px;
}

.gallery img {
	width: 100%;
	height: auto;
}

.contact-button {
	margin-top: 20px;
	display: inline-block;
	background-color: #4285f4;
	color: #fff;
	padding: 10px 20px;
	border-radius: 5px;
	text-decoration: none;
	font-size: 16px;
	transition: all 0.3s ease;
}

.contact-button:hover {
	background-color: #0d47a1;
}
```

### Este código utiliza CSS Grid para crear una cuadrícula de imágenes con 4 columnas y un espacio de 10px entre ellas. Las imágenes en la galería ocupan el 100% del ancho disponible en las columnas de la cuadrícula, y su altura se ajusta automáticamente para mantener la relación de aspecto original de cada imagen.