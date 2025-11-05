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
