// Add to cart functionality
const addToCartButtons = document.querySelectorAll('.product-card button');

addToCartButtons.forEach(button => {
	button.addEventListener('click', () => {
		alert('Item added to cart!');
	});
});