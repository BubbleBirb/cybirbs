# Charadex

The free and easy way to log your species designs and show it off!

### Disclaimer

I'm not especially good at JS, so I apologize in advance if anyone who knows their stuff sees it and barfs. Obviously I encourage any optimizing of this product. I'm also extremely new to github and all of this so I'm very sorry for any glaring mistakes I may make slhfsdklf

---

### Pros

- Easy masterlist submissions - literally just add a row and the info, then just keep going about your business!
- (Can be) completely free to run, as long as you're hosting somewhere like gitpages or neocities.
- Can be used to keep up with the characters you sell as well!
- Comes with a small CSS sheet that you can use to edit the page a bit more. You _will_ need some CSS knowledge for more advanced styling, but there are variables that allow you to switch out the colors rather easily.

### Cons

- Absolutely not meant for species with designs in the thousands. It'll end up being too much of a straight for google sheets. If you have that many design, I recommend lorekeeper or commissioning someone with fullstack knowledge to help you out.
- Hard to edit the sheet to include more information. If you absolutely don't know anything about sheets or JS, you're going to have a really bad time.
- No search function or _real_ pagination function on the outward page. (I'm not smart enough to add these in yet...but one day.)
- Older computers might shit themselves, I'm so sorry google sheets is like that.

---

# Getting Started

First and foremost, you'll need a clean version of the google sheet. [Grab it here!](http://www.google.fr/ "Named link title")

## Sheet Anatomy

### Options

This lets you change a few things, such as the filler MYO image and the ID prefix, to better fit your species and taste. 

### Log

The log you'll be inputting info into.

- `Transaction ID` - This automatically adds a transaction number to your new entry.
- `ID Number` - If you're logging a new design, you leave this empty. But if you're logging a transaction, make sure to fill in the ID so it updates the ML Entry!
- `Image` - Image of the design, leave empty if no design.
- `Owner` - Owner of design at time of logging.
- `Artist` - Artist of image.
- `Designer` - Designer of design.
- `Worth` - Design's worth.
- `Status` - Whether it's okay to resale, trade, or gift a design - or if the design is voided.
- `Cooldown` - Designs can be traded after this date. **Small warnings will pop up in these cells,** don't worry about them, they sheet is working as intended.
- `Design Type` - Type of design.
- `Transaction Type` - If it's a new entry or a traded design, etc.
- `Proof` - Proof of transaction.

  Some Warnings |
  :------------- |
  Log entries **should _not_** be deleted. This will mess shift everything on the list.  |
  Every new transaction should be logged - I do **not** recommend going back to the original entry and trying to edit in an owner or something.  |
  I do not recommend logging URLs in Owner, Artist, & Designer. The JS on the site won't read it if it's hotlinked, and it looks bad as a regular link. You also can't log multiple people this way.  |

### Original Log

This is the log all of new entries with be added to.

### Transaction Log

All of the transactions will sort into this log. This serves two purposes - to make it easier for the final list to sort through information, and so you have a log to look back on in case any discrepancies arise.

### Masterlist

This is the final conglomerate of the logs, and the sheet you'll be pulling information from.

This is also the sheet you mark notes on! If you have anything to add on the design, add in the Notes column.

## How to add an entry

![picture](https://i.imgur.com/JRnl1wv.gif)

<details>
   <summary>And here's how transaction logs look.</summary>
   <img src="https://i.imgur.com/7qaOCRp.gif">
</details>

**Step One:** Right click on row 2 and then click Insert 1 Above.

**Step Two:** Add in the information like normal.

**Step Three:** You're done! But make sure to check the bank once you're done in case something doesn't look right.

## Changing Usernames

![picture](https://i.imgur.com/mHSWmWR.gif)

**Step One:** In the log, press `CTRL + F` and then type in the old username.

**Step Two:** Press the button with 3 dots and enter the Replace with portion with the new username.

**Step Three:** Press Replace all and you're done!

## Publishing Sheet

![picture](https://i.imgur.com/HRuSvYv.gif)

**Step One:** Go to `File` and select `Publish to Web`.

**Step Two:** Select the `Master Sheet` document ONLY.

**Step Three:** Publish!

  Permission Warnings |
  :------------- |
  If you ever need to add mods into the sheet, **do NOT allow everyone to edit via link**. That will allow anyone to come in and edit whatever they like. You need to click `Share` and add people via their emails instead. |

---

# Hosting

I will only be showing you how to host on neocities. It is probably easier to host on github using gitpages but you need to know how to use github to really utilize it. I might make a tutorial later, but unfortunately right now I don't have the time :'3c

Without further ado.

First, you'll need to sign up to [neocities](https://neocities.org/). Then go to `Edit Site`, you'll see a menu with 4 files. **Delete every file except the `Index` file.**

Head up _this_ page and click the button that says `Code` then hit `Download Zip`. You'll need to unzip the file - anywhere will do!

Open the folder named `charadex-master` and highlight all the files. Drag and drop them into the Neocities dashboard.

You should now have an up and running site!!!

## Importing Your Sheet

Right now, the site should be importing from my example sheet. Grab your sheet ID - it's located in the URL. 

**Example:** /spreadsheets/d/`1vVtBIK-ftiPTTzPnn40uLAafWJrGvqIrW1GFYo1gmrM`/edit#gid=0

Edit the `Index` file and scroll to the bottom of the `Index` file, is a code that says `var = "1vVtBIK-ftiPTTzPnn40uLAafWJrGvqIrW1GFYo1gmrM"` replace this ID with yours and save. You should be good to go!

**If** you have shifted the sheets around for whatever reason, the second number needs to be the page number of the sheet. Like right now, it's the 5th sheet in the document - if you move it right behind `Options`, it would be the 2nd. So the number would change to 2.

---

# Credits
