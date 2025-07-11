// js/theme.js
function toggleTheme() {
  document.body.classList.toggle("dark-theme");

  // Save preference to localStorage
  if (document.body.classList.contains("dark-theme")) {
    localStorage.setItem("theme", "dark");
  } else {
    localStorage.setItem("theme", "light");
  }
}

// Apply saved theme on page load
window.addEventListener("DOMContentLoaded", () => {
  if (localStorage.getItem("theme") === "dark") {
    document.body.classList.add("dark-theme");
  }
});
