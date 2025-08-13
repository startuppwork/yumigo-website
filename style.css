// Smooth scrolling for navigation links
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
  anchor.addEventListener('click', function(e) {
    e.preventDefault();
    document.querySelector(this.getAttribute('href')).scrollIntoView({
      behavior: 'smooth'
    });
  });
});

// Terms Modal
const termsModal = document.getElementById('terms-modal');
const termsLink = document.getElementById('terms-link');
const closeBtn = document.querySelector('.close');

termsLink.addEventListener('click', (e) => {
  e.preventDefault();
  termsModal.style.display = 'block';
});

closeBtn.addEventListener('click', () => {
  termsModal.style.display = 'none';
});

window.addEventListener('click', (e) => {
  if (e.target === termsModal) {
    termsModal.style.display = 'none';
  }
});
