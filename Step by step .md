step 0: git init -Project git ke control me aa jayega (hidden .git create ho jayega)

local Project aur Github ke bich connection bn jayega

step 0.1: create Repo on github copy the link :
git remote add origin https://github.com/San1357/01-Portfolio.git

step 0.2:

First Push to GitHub

git add .
git commit -m "Initial commit"
git branch -M main # optional: renames branch to main
git push -u origin main

step 1: Add Boilerplate

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Your Name - Portfolio</title>
</head>
<body>
    
</body>
</html>

also learn (semantic Element kya hota hai ?)

✅ Meaning

Semantic HTML = Meaningful tags jo browser & developer ko batate hain ki content kya represent karta hai.

🧠 Why Use?

SEO better

Accessible for screen readers

Code clean & readable

🆚 Semantic vs Non-Semantic

Non-Semantic: <div>, <span> → Meaning nahi batate

Semantic: <header>, <nav>, <main>, <section>, <article>, <footer> → Meaning batate

⭐ Important Semantic Tags

<header> • <nav> • <main> • <section> • <article> • <aside> • <footer> • <figure> • <figcaption>

step2:Portfolio Page ka full structure banayenge

7 main sections add karenge:

Header (Navigation)

Hero / Intro

About Me

Skills

Projects

Contact

Footer

page structure:
header
main
footer

header ke andar nav
main ke andar section (all)
footer ke andar copyright

---

step 3:

added content & improved semantic by adding actual content

step4:
Add Accessibility + SEO Improvements

Add Accessibility:
Website ko aise banana ki visually impaired, keyboard users, screen reader users bhi use kar sake.

Bad accessibility:
No alt in images
Buttons without labels
Only mouse support

improved accessebility:
Add alt="description"
Add aria-label
Add keyboard focus support

SEO Improvements:

Website ko aise structure aur code karna ki Google easily samajh sake aur ranking improve ho.

Example: Bad seo
H1 missing Add 1 proper <h1>
No meta tags Add meta description
No semantic tags

Goood seo :
Add 1 proper <h1>
Add meta description
Use semantic tags

1- Add Language, Description & Author (SEO):

2- Add Aria Labels for Better Accessibility:

Example:

Without aria-label:

Screen reader: "Form" (but kaunsa form?)
User confuse ho sakta hai.

With aria-label:

Screen reader बोलेगा:

"Contact Form"

aria-label elements ko meaningful name deta hai taaki screen readers unhe clearly announce kar sake.
Ye visually impaired users ke liye website ko accessible, understandable, aur user-friendly banata hai.

Screen Reader Kya Karta Hai?

Website ke text ko audio me read karta hai

Button, links, forms ka role bataata hai

Keyboard ke through navigate karne me help karta hai

Alt text, aria labels, headings — sab ko read karta hai

For example: <button>Search image</button>
Screen reader बोलेगा:

“Search Button”

Screen reader बोलेगा:

“Search Button”

3- Add Skip to Main Content Link (Professional UX):

Jo log mouse use nahi kar sakte (blind, disabled, or keyboard-only users), unhe website ke header, menu, ads, sidebar sab skip karke seedhe main content par jump karne ka option milta hai.

Normally, unhe tab-tab-tab karte hue 15–20 elements cross karne padte.
Is link se 1 tab me direct content par pahunch jaate.

Screen reader users ke liye baar-baar menu sunna irritating hota hai:

"Home, About, Services, Contact…"
every time page loads!

Skip link bolta hai:

“Skip to main content”

User direct core content sun sakta hai—UX improve.

Jab user TAB press karta hai, yeh link visible ho jata hai →
user enter dabata hai → page #hero (main content section) par jump kar jata hai.

4- Add Open Graph Tags (for LinkedIn/WhatsApp preview):

Without OG tags, jab tum link share karte ho to random or ugly preview aata hai — kabhi code dikh jata hai, kabhi kuch bhi text nahi aata.

With OG tags, preview clean, attractive aur controlled dikhai deta hai.

WhatsApp / LinkedIn preview example:

Title: “Aayush Gupta - Portfolio”
Description: “Aspiring Full Stack Developer learning through real-world projects.”

Isse log click karne me confident feel karte hain.

---

Styling (CSS):

step1: Link Css file to html file.

step2: CSS reset + Basic theme

step3: style Header + Nav bar

step 4:style the hero section

step 5 :Global Sections spacing

step 6: style about section

step 7: skills styled

step 8: Projects section styled

step 9:Style Contact Form
