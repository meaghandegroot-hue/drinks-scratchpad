# Drinks Scratchpad

A pocket scratchpad for serving drinks. It holds orders between the table and the POS so nothing has to be written on paper or kept in your head.

## What it does

- **Dictate a whole round.** Say or type "one Coors Light for Ken, one Caesar for the lady with the witch hat, three more shots for the table in the corner" and it splits into separate orders. Say "comma" between orders when dictating.
- **Check before adding.** A sheet shows the split orders so misheard words can be fixed.
- **Quick add.** Beer or mixed, bottle or draft, the first 3 letters of the drink, how many, who it is for.
- **Cash or tab on every order.** Marked when the order is added, shown on the card, and a "Collect cash" or "On tab" reminder appears when the drink is ready to bring out.
- **Same again.** Remembers each person's last round and repeats it with one tap.
- **Open tabs.** Lists everyone on a tab with their drinks and how many are not rung in yet.
- **Photos.** Attach a photo to a person from the camera or photo library.

## Running it

It is a single static file with no build step and no dependencies. Open `index.html` in a browser, or serve the folder with any static host (for example GitHub Pages).

## Notes

- Everything is saved in the browser's `localStorage`. Nothing leaves the device, and data does not move between browsers or devices.
- Dictation uses the phone keyboard's own microphone button. The page does not access the microphone.
- The only external request is the Google Fonts stylesheet; the page works without it.
- Written for phone-sized screens.
