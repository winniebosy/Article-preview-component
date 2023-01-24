# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

- Very Dark Grayish Blue: hsl(217, 19%, 35%)
- Desaturated Dark Blue: hsl(214, 17%, 51%)
- Grayish Blue: hsl(212, 23%, 69%)
- Light Grayish Blue: hsl(210, 46%, 95%)

## Typography

### Body Copy

- Font size: 13px

### Headings

- Family: [Manrope](https://fonts.google.com/specimen/Manrope)
- Weights: 500, 700

## Icons

We provide SVGs for the social icons. But please feel free to use a font icon library if you like. Some suggestions can be found below:

- [Font Awesome](https://fontawesome.com)
- [IcoMoon](https://icomoon.io)
- [Ionicons](https://ionicons.com)





h1 {
    text-align: center;
    color: var(--font-color-primary)
}

.article-container {
    display: flex;
    flex-direction: row;
    flex-wrap: nowrap;
    width: 90%;
    height: 500px;
    justify-content: center;
    margin-left: auto;
    margin-right: auto;
    box-shadow: 3px 5px 5px 5px grey;
}

.article-img {
    width: 50%;
    height: 100%;
    background-image: url('images/drawers.jpg');
    background-repeat: no-repeat;
    background-position: center center;
    background-size: auto;
    object-fit: fill;
}

.article-content {
    width: 50%;
    padding: 0 0 0 1rem;
    line-height: 1.4;
    font-size: calc(1.02 * var(--font-size))
}

.article-content h2 {
    text-align: center;
    color: var(--font-color-complementary);
    font-size: 1.8rem;
    margin: 3rem;
}

.description {
    font-size: 1.4rem;
}

.article-profile-info {
    display: flex;
    flex-direction: row;
    gap: 3rem;
}

.article-social-media {
    background-color: var(--font-color-complementary);
}

.article-social-media a {
    text-decoration: none;
}

p .date {
    color: var(--font-color-primary);
}

.article-profile-pic {
    width: 70px;
    height: 70px;
    border-radius: 50%;
    margin-top: 0.8rem;
    margin-left: -0.5rem;
    box-shadow: 2px 1px rgb(148, 148, 148);
}

.date {
    margin-top: -0.8rem;
}

button {
    height: 60px;
    width: 60px;
    border-radius: 50%;
    background-color: var(--font-color-complementary);
    color: #ffffff;
    cursor: pointer;
    margin-top: 1rem;
}