# Access Day

Access Day is a website for a fictional one-day conference about web accessibility. It helps visitors learn about the event, check the schedule, meet the speakers, and try a demo registration form.

> **Note:** This event is fictional and created for learning and portfolio purposes.

## Live site
[View the live site](https://enzokozo.github.io/access-day/)

## Project status

✅ The first version, built with HTML only, is complete. The next phase is styling with CSS.

## Features

Included in the first version:

- [x] Home page with event information
- [x] Schedule with talks and workshops
- [x] Speaker profiles
- [x] Demo registration form
- [x] Registration confirmation page
- [x] Semantic and accessible HTML structure

## Accessibility

All pages were checked with:

- The W3C Markup Validator
- Lighthouse, WAVE, and axe DevTools
- Keyboard-only navigation, including the skip link and the form
- Windows Narrator with the Brave browser
- Reflow at a 320 px viewport width, with no horizontal scrolling

## Known limitations

The registration form is only a demo. It uses method="get", so the submitted data appears in the URL, and nothing is stored.

Some links and form controls have small touch targets, because the pages still use the browser's default styles. This will be fixed in the CSS phase.

## Technologies

- HTML5

## How to run

1. Clone the repository:

   ```bash
   git clone https://github.com/enzokozo/access-day.git
   ```

2. Open the `access-day` folder.
3. Open `index.html` in your browser.

## Next steps

- Build a mobile-first layout with CSS
- Adapt the schedule table to small screens
- Display the speaker profiles as cards
- Increase the size of touch targets

## Credits

Speaker illustrations from [Open Peeps](https://openpeeps.com) by Pablo Stanley, downloaded from Blush and licensed under CC0. They are not covered by this project's MIT License.

## License

This project is licensed under the [MIT License](LICENSE).