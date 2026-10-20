# The Digital Miner

![The Digital Miner logo](images/readmeDigitalMiner.png)

A blog about cryptocurrency, built as my first exam project at Noroff (frontend development)
in early 2024. I chose the theme, designed the site and developed it myself.

**Live site:** https://graceful-crepe-072f72.netlify.app/

## What it includes

- 12 blog posts, a blog list and a page for each post
- Image carousel on the home page
- Modal for viewing images
- Contact form with JavaScript validation
- Hamburger menu for mobile
- Pages for crypto charts, about, contact and a disclaimer

## WordPress as a headless CMS

The posts were originally written in WordPress and loaded through the WordPress REST API,
using Advanced Custom Fields (ACF) for the title, author, category, sections and image.
The rest of the site is plain HTML, CSS and JavaScript.

In November 2024 I moved the posts into a local `posts.json`, because the WordPress site
was going to shut down. The JSON keeps the same structure as the API response, so the fetch
and render code only needed a new URL.

## The assignment

Build a blog with a theme of your own choice that uses the WordPress REST API, and
include a carousel, a modal, JavaScript form validation and at least 12 posts.

## Built with

- HTML
- CSS
- JavaScript (ES modules, Fetch API)
- WordPress REST API + ACF (originally), now a local JSON file
- Netlify (hosting)

## Looking back

- All images and text on the site were generated with Midjourney and ChatGPT.
- I struggled with ACF. Every post had to follow the same fixed structure (four headings and
  four paragraphs), and I felt bound by the structure I had set up. Today I would use a more
  flexible content model, so posts can vary, and filter the articles better.
- This was my first experience with filtering and slicing arrays in JavaScript.

## Contact

- [LinkedIn](https://www.linkedin.com/in/bart-van-den-berg-b90219155/)
