# WINGS: An Ethical Fashion Website

**A one-page website for a fictional fashion brand built around sustainable and ethical clothing.**

Fast fashion has a cost, and more people want to know where their clothes come from. WINGS is a website concept for a brand that answers that question: organic and renewable fabrics, natural dyes, recycled materials, fair trade and cruelty-free sourcing, all summed up in its "6 R's" (Reduce, Refuse, Rethink, Repair, Reuse, Recycle).

It was built during my **Full Stack Web Development internship at Varcons Technologies** in June 2023, as a hands-on project to practise building a complete, responsive web page.

> The brand, the collections and the claims on the page are **sample content for a demonstration**, not a real company.


---

## The team

A team project by **Sumukha S**, **Darshan K** and **Soundarya R**.


---

## What is on the page

- **A full-width hero section** with a background photo and a transparent navigation bar (Home, Collections, Products, About Us). On phones the menu collapses into a slide-out drawer.
- **Three product stories**, each with a photo and short description: *Women* (renewable fabrics and plant dyes), *Men* (organic cotton and redesigned clothes) and *Accessories* (recycled rubber shoes and biodegradable packaging). Clicking a photo opens it full size.
- **Two parallax image banners** that move as you scroll.
- **An About Us section with tabs:** *Design details* lists the new collections, and *Fashion details* lists the product categories (Women, Men, Kids, Accessories, Shoes).
- **A contact form** with email and message fields.
- **A footer** with the "6 R's" and links to social media.

The layout is responsive, so it adapts from desktop to mobile.

## Tech stack

HTML5 · CSS3 · [Materialize CSS](https://materializecss.com/) 1.0.0 · jQuery 3.6 · Material Icons

Materialize provides the grid, navigation, tabs, parallax effect and image zoom. The small custom CSS block sets the hero image and its mobile height.

## Run it yourself

1. Download or clone the repository.
2. Put the page's images in the same folder as the HTML file: `main.jpg`, `leather.jpg`, `jeans.jpg`, `watch.jpg`, `p1.jpg` and `p2.jpg`. *(Add them to the repo, and only use images you have the right to share.)*
3. Open the HTML file in your browser. You need an internet connection, because Materialize, jQuery and the icon fonts load from CDNs.

---

## What is not built, and known issues

I would rather be upfront about what this is, so here is an honest list.

- **There is no back end in this code.** The contact form has no action or handler, so pressing Submit sends nothing. *(If you built a back end or database for the internship, add that code to the repository and describe it here. If not, remove "back end" from your role above.)*
- **The navigation links and tabs don't work.** The links are written `herf` instead of `href`, so the menu items don't go anywhere and the *Design details* and *Fashion details* tabs don't switch. This is a one-word fix per link.
- **Social links point nowhere.** Facebook and Instagram link to `#`.
- **Some text and class names have typos**, such as "deatils", "Cruelity-free", "Tommorow's" and the misspelled `perfix` and `offest-12` classes, so those styles don't apply.
- **Images have no alt text,** which hurts accessibility.
- **A Font Awesome Pro stylesheet is linked but never used.** It also needs a licence, so it can be removed.

## What I would improve next

- Fix the `href` typos and the spelling mistakes
- Connect the contact form to a back end (for example Flask or Node) that stores or emails the messages
- Add real Collections and Products pages with a product catalogue
- Add alt text and test accessibility
- Publish it with GitHub Pages

## Authors

Sumukha S, Darshan K and Soundarya R
Varcons Technologies, Full Stack Web Development Internship, June 2023

## License

*(Agree this with your teammates, and check that Varcons allows the work to be published. If everyone agrees, MIT is a sensible choice.)*
