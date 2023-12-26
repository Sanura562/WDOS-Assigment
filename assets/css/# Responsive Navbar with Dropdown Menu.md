 # Responsive Navbar with Dropdown Menu

This is a responsive navbar with a dropdown menu. It is built using HTML and CSS. The navbar is fixed to the top of the page and it changes its appearance when the screen size is reduced.

## Step 1: HTML Structure

The HTML structure of the navbar is as follows:

```html
<header>
  <nav class="navbar">
    <div class="logo">
      <a href="#">Logo</a>
    </div>
    <ul class="links">
      <li><a href="#">Home</a></li>
      <li><a href="#">About</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
    <button class="toggle_btn">
      <i class="fas fa-bars"></i>
    </button>
  </nav>
</header>
```

The navbar consists of a logo, a list of links, and a toggle button. The toggle button is used to show or hide the dropdown menu when the screen size is reduced.

## Step 2: CSS Styles

The CSS styles for the navbar are as follows:

```css
/* Navbar */
.navbar {
  width: 100%;
  height: 69px;
  max-width: 1700px;
  margin: 0 auto;
  display: flex;
  align-items: center;
  justify-content: space-between;
  position: relative;
}

.navbar .logo a {
  font-size: 1.5rem;
  font-weight: bold;
}

.navbar .links {
  display: flex;
  gap: 2rem;
  font-size: 20px;
  text-decoration: none;
}

.navbar .toggle_btn {
  color: #eee;
  font-size: 1.5rem;
  cursor: pointer;
  display: none;
}

/* Dropdown_menu */
.dropdown_menu {
  display: none;
  position: absolute;
  right: 2rem;
  top: 60px;
  width: 300px;
  background: rgba(255, 255,)

}