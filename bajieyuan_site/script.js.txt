document.getElementById('contact-form').addEventListener('submit', function(e) {
    e.preventDefault();
    alert('感谢你的留言！我会尽快回复。');
    this.reset();
});