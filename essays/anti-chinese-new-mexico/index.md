---
title: "Chinese Ordered to 'Git' in Territorial New Mexico"
layout: scrollstory
header-image: "Images/tom-ying-restaurant.png"
thumbnail: "Images/tom-ying-restaurant.png"
summary: An 1885 Silver City notice shows how newspapers made Chinese residents seem removable.
---

<style>
:root {
  --bg: #f4eadb;
  --paper: #fff8ec;
  --paper-soft: #f8efdf;
  --paper-deep: #ead8bc;
  --ink: #211812;
  --ink-soft: #4e3e32;
  --muted: #7a6a5b;
  --brown: #2a1b13;
  --brown-soft: #3a2519;
  --copper: #9b572f;
  --copper-dark: #6d321b;
  --gold: #d9ae5f;
  --gold-soft: #f0d8a1;
  --line: #d5bea0;
  --line-soft: rgba(213, 190, 160, 0.55);
  --shadow: rgba(35, 22, 13, 0.16);
  --shadow-deep: rgba(35, 22, 13, 0.24);
}

html {
  scroll-behavior: smooth;
}

body {
  background:
    radial-gradient(circle at 8% 0%, rgba(155, 87, 47, 0.18), transparent 28rem),
    radial-gradient(circle at 92% 10%, rgba(217, 174, 95, 0.18), transparent 26rem),
    radial-gradient(circle at 50% 115%, rgba(106, 50, 27, 0.10), transparent 30rem),
    linear-gradient(180deg, #efe1cc 0%, var(--bg) 32%, #fbf6ed 100%);
  color: var(--ink);
}

body::before {
  content: "";
  position: fixed;
  inset: 0;
  pointer-events: none;
  background-image:
    linear-gradient(rgba(42, 27, 19, 0.026) 1px, transparent 1px),
    linear-gradient(90deg, rgba(42, 27, 19, 0.026) 1px, transparent 1px);
  background-size: 36px 36px;
  z-index: -2;
}

body::after {
  content: "";
  position: fixed;
  inset: 0;
  pointer-events: none;
  background:
    linear-gradient(90deg, rgba(255,255,255,0.18), transparent 12%, transparent 88%, rgba(255,255,255,0.18)),
    radial-gradient(circle at center, transparent 52%, rgba(42, 27, 19, 0.05));
  z-index: -1;
}

main,
.page-content,
.wrapper,
.post-content {
  max-width: 960px;
}

.post-content {
  position: relative;
  font-size: 1.08rem;
  line-height: 1.82;
}

.post-content::before {
  content: "";
  position: absolute;
  top: 35rem;
  bottom: 0;
  left: -2.3rem;
  width: 2px;
  background: linear-gradient(to bottom, transparent, rgba(155, 87, 47, 0.38), rgba(217, 174, 95, 0.24), transparent);
  border-radius: 999px;
}

.post-content > p {
  margin: 1.15rem 0;
  color: var(--ink);
}

.post-content > p:hover {
  background: rgba(255, 248, 236, 0.34);
  box-shadow: -0.45rem 0 0 rgba(155, 87, 47, 0.12);
}

.essay-hero {
  position: relative;
  min-height: clamp(430px, 62vh, 680px);
  margin: 1.2rem auto 3.3rem auto;
  padding: clamp(2rem, 5vw, 4rem);
  display: flex;
  flex-direction: column;
  justify-content: flex-end;
  overflow: hidden;
  border-radius: 30px;
  background:
    linear-gradient(90deg, rgba(18, 10, 6, 0.92) 0%, rgba(35, 20, 12, 0.78) 42%, rgba(35, 20, 12, 0.35) 100%),
    linear-gradient(0deg, rgba(18, 10, 6, 0.88) 0%, rgba(18, 10, 6, 0.18) 52%, rgba(18, 10, 6, 0.35) 100%),
    url("Images/tom-ying-restaurant.png");
  background-size: cover;
  background-position: center;
  box-shadow:
    0 30px 70px rgba(35, 22, 13, 0.34),
    inset 0 0 0 1px rgba(255,255,255,0.18);
}

.essay-hero::before {
  content: "";
  position: absolute;
  inset: 16px;
  border: 1px solid rgba(255, 248, 236, 0.35);
  border-radius: 22px;
  pointer-events: none;
  z-index: 1;
}

.essay-hero::after {
  content: "";
  position: absolute;
  inset: 0;
  background:
    radial-gradient(circle at 20% 18%, rgba(255, 232, 176, 0.25), transparent 18rem),
    radial-gradient(circle at 90% 80%, rgba(155, 87, 47, 0.22), transparent 24rem);
  pointer-events: none;
  z-index: 0;
}

.essay-hero h1,
.essay-hero p,
.essay-hero .hero-rule {
  position: relative;
  z-index: 2;
}

.essay-hero h1 {
  max-width: 900px;
  margin: 0;
  color: #fff7e8;
  font-size: clamp(3rem, 9vw, 7rem);
  line-height: 0.88;
  letter-spacing: -0.075em;
  text-wrap: balance;
  text-shadow:
    0 4px 20px rgba(0,0,0,0.72),
    0 1px 2px rgba(0,0,0,0.95);
}

.essay-hero p {
  max-width: 730px;
  margin: 1.45rem 0 0 0;
  color: #fff0cf;
  font-size: clamp(1.12rem, 2.2vw, 1.45rem);
  line-height: 1.5;
  font-weight: 600;
  text-shadow:
    0 3px 12px rgba(0,0,0,0.72),
    0 1px 2px rgba(0,0,0,0.95);
}

.essay-hero .hero-rule {
  width: min(100%, 760px);
  height: 2px;
  margin-top: 1.6rem;
  background: linear-gradient(90deg, var(--gold), rgba(255, 248, 236, 0.55), transparent);
  box-shadow: 0 0 18px rgba(217, 174, 95, 0.35);
}

.post-content > h1 {
  position: relative;
  margin-top: 2rem;
  padding-bottom: 0.8rem;
  color: var(--brown);
  border-bottom: 4px double var(--line);
  font-size: clamp(2.1rem, 4vw, 3.2rem);
  line-height: 1.04;
  letter-spacing: -0.04em;
}

.post-content > h1::after {
  content: "";
  position: absolute;
  left: 0;
  bottom: -0.55rem;
  width: 5.5rem;
  height: 0.18rem;
  background: linear-gradient(90deg, var(--copper), transparent);
  border-radius: 999px;
}

.post-content > h1 + p::first-letter {
  float: left;
  font-size: 4.9rem;
  line-height: 0.82;
  padding: 0.18rem 0.52rem 0 0;
  color: var(--copper-dark);
  font-weight: 800;
  font-family: Georgia, serif;
}

.post-content > h2 {
  position: relative;
  margin-top: 3.35rem;
  margin-bottom: 1.25rem;
  padding: 1.12rem 1.25rem 1.12rem 1.45rem;
  color: var(--brown);
  background:
    linear-gradient(90deg, rgba(155, 87, 47, 0.18), rgba(255, 248, 236, 0.86)),
    linear-gradient(180deg, rgba(255,255,255,0.58), rgba(255,255,255,0.08)),
    var(--paper);
  border-left: 8px solid var(--copper);
  border-radius: 0 20px 20px 0;
  box-shadow:
    0 14px 30px rgba(35, 22, 13, 0.09),
    inset 0 0 0 1px rgba(255,255,255,0.52);
  font-size: clamp(1.45rem, 3vw, 2.08rem);
  line-height: 1.1;
  letter-spacing: -0.03em;
}

.post-content > h2::before {
  content: "";
  position: absolute;
  left: -1.05rem;
  top: 50%;
  width: 0.65rem;
  height: 0.65rem;
  transform: translateY(-50%);
  background: var(--gold);
  border: 3px solid var(--bg);
  border-radius: 50%;
  box-shadow: 0 0 0 1px rgba(155, 87, 47, 0.35);
}

.post-content > h2::after {
  content: "";
  position: absolute;
  left: 1.45rem;
  right: 1.45rem;
  bottom: 0.42rem;
  height: 1px;
  background: linear-gradient(90deg, rgba(155, 87, 47, 0.38), transparent);
}

.post-content > h2 + p {
  padding: 1.15rem 1.25rem;
  background:
    linear-gradient(135deg, rgba(255,255,255,0.72), rgba(248, 239, 223, 0.72)),
    var(--paper-soft);
  border: 1px solid var(--line-soft);
  border-radius: 18px;
  box-shadow:
    0 12px 26px rgba(35, 22, 13, 0.08),
    inset 0 0 0 1px rgba(255,255,255,0.55);
}

.post-content > h3 {
  position: relative;
  margin-top: 1.9rem;
  padding-top: 0.45rem;
  color: var(--copper-dark);
  font-size: 1.12rem;
  letter-spacing: 0.08em;
  text-transform: uppercase;
}

.post-content > h3::before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 3.2rem;
  height: 0.18rem;
  background: linear-gradient(90deg, var(--copper), transparent);
  border-radius: 999px;
}

.post-content > p:nth-of-type(2),
.post-content > p:nth-of-type(8),
.post-content > p:nth-of-type(16),
.post-content > p:nth-of-type(23) {
  padding: 1.08rem 1.25rem;
  background:
    linear-gradient(180deg, rgba(255,255,255,0.62), rgba(255,255,255,0.14)),
    var(--paper-soft);
  border: 1px solid rgba(213, 190, 160, 0.95);
  border-radius: 18px;
  box-shadow:
    0 10px 24px rgba(35, 22, 13, 0.07),
    inset 0 0 0 1px rgba(255,255,255,0.48);
}

.post-content > p:nth-of-type(2)::before,
.post-content > p:nth-of-type(8)::before,
.post-content > p:nth-of-type(16)::before,
.post-content > p:nth-of-type(23)::before {
  content: "";
  display: block;
  width: 4rem;
  height: 0.14rem;
  margin-bottom: 0.65rem;
  background: linear-gradient(90deg, var(--gold), transparent);
  border-radius: 999px;
}

.image-card {
  position: relative;
  margin: 2.25rem auto 3rem auto;
  padding: 1.05rem;
  background:
    linear-gradient(180deg, rgba(255,255,255,0.7), rgba(255,255,255,0.12)),
    radial-gradient(circle at top right, rgba(217, 174, 95, 0.16), transparent 18rem),
    var(--paper);
  border: 1px solid var(--line);
  border-radius: 26px;
  box-shadow:
    0 26px 54px rgba(35, 22, 13, 0.17),
    inset 0 0 0 1px rgba(255,255,255,0.62);
  text-align: center;
  overflow: hidden;
}

.image-card::before {
  content: "";
  position: absolute;
  inset: 12px;
  border: 1px solid rgba(155, 87, 47, 0.2);
  border-radius: 19px;
  pointer-events: none;
}

.image-card::after {
  content: "";
  position: absolute;
  width: 12rem;
  height: 12rem;
  right: -5rem;
  top: -5rem;
  background: radial-gradient(circle, rgba(155, 87, 47, 0.14), transparent 70%);
  pointer-events: none;
}

.image-card img {
  position: relative;
  z-index: 1;
  width: 100%;
  max-width: 650px;
  height: auto;
  display: block;
  margin: 0 auto;
  border-radius: 15px;
  box-shadow:
    0 14px 30px rgba(35, 22, 13, 0.24),
    0 0 0 8px rgba(255, 248, 236, 0.65);
  filter: contrast(1.05) sepia(0.13);
}

.image-card figcaption {
  position: relative;
  z-index: 1;
  max-width: 700px;
  margin: 1.05rem auto 0 auto;
  color: var(--muted);
  font-size: 0.95rem;
  line-height: 1.5;
}

.image-card figcaption cite {
  display: block;
  margin-top: 0.6rem;
  padding: 0.65rem 0.75rem 0 0.75rem;
  border-top: 1px solid rgba(155, 87, 47, 0.2);
  color: #76675a;
  font-size: 0.82rem;
  font-style: normal;
  line-height: 1.45;
}

.post-content > h2:nth-of-type(7) ~ p {
  padding: 0.85rem 1rem;
  background: rgba(255, 248, 236, 0.68);
  border-left: 4px solid rgba(155, 87, 47, 0.42);
  border-radius: 0 12px 12px 0;
}

em {
  color: var(--copper-dark);
}

a {
  color: var(--copper-dark);
  text-decoration-color: rgba(155, 87, 47, 0.45);
  text-decoration-thickness: 0.08em;
  text-underline-offset: 0.18em;
}

a:hover {
  color: var(--brown);
  text-decoration-color: var(--brown);
}

strong {
  color: var(--copper-dark);
}

hr {
  border: 0;
  height: 1px;
  background: linear-gradient(90deg, transparent, var(--line), transparent);
  margin: 2rem 0;
}

.post-content ul {
  padding-left: 1.25rem;
}

.post-content li::marker {
  color: var(--copper);
}

::selection {
  background: rgba(217, 174, 95, 0.42);
}

@media (max-width: 760px) {
  .post-content::before {
    display: none;
  }

  .essay-hero {
    min-height: 470px;
    padding: 1.45rem;
    border-radius: 22px;
    background:
      linear-gradient(0deg, rgba(18, 10, 6, 0.9) 0%, rgba(18, 10, 6, 0.42) 68%, rgba(18, 10, 6, 0.35) 100%),
      url("Images/tom-ying-restaurant.png");
    background-size: cover;
    background-position: center;
  }

  .essay-hero h1 {
    letter-spacing: -0.058em;
  }

  .post-content {
    font-size: 1rem;
    line-height: 1.72;
  }

  .post-content > h2 {
    padding: 0.95rem 1rem;
  }

  .post-content > h2::before {
    display: none;
  }

  .image-card {
    padding: 0.78rem;
    border-radius: 18px;
  }

  .image-card img {
    box-shadow:
      0 10px 22px rgba(35, 22, 13, 0.20),
      0 0 0 5px rgba(255, 248, 236, 0.68);
  }
}
</style>

<section class="essay-hero">
  <h1>Chinese Ordered to 'Git' in Territorial New Mexico</h1>
  <p>An 1885 Silver City notice shows how newspapers made Chinese residents seem removable.</p>
  <div class="hero-rule"></div>
</section>

# Introduction

On December 3, 1885, the Golden Era, a Lincoln, New Mexico, newspaper, printed a notice from Silver City: “The citizens of Silver City have had a round-up among the Chinese, and have ordered them to ‘git.’”¹ Though short, this sentence records an attempt to expel Chinese residents and uses language that implies routine action.

This page argues that the Silver City notice demonstrates how newspaper language actively denied the Chinese of recognition as legitimate community members in New Mexico. It functions as evidence of civic unmaking: by referring to the entire group as "the Chinese" and juxtaposing them with "citizens," the notice constructs Chinese residents as outsiders, vulnerable to expulsion. This process is key in forming AANHPI and New Mexico history because it made the exclusion and delegitimization of Chinese residents visible through common reporting.

First, we’ll take a close look at the Golden Era notice, especially the words “citizens,” “round-up,” and “git.” Next, we’ll compare this notice to other articles in the same newspaper issue to highlight how Chinese residents were represented differently. After that, it puts the Silver City notice alongside reports from Deming, Socorro, Raton, and Central City, tracking patterns of anti-Chinese pressure, labor needs, population counts, protection, and legal vulnerability. Finally, it connects these local stories to the larger history of Chinese exclusion in the West and to historians’ later attempts to recover the lives of individual Chinese New Mexicans from scattered records.

## The Meaning of “Round-Up”

Looking at the language, “round-up” is the strongest word in the notice. The same issue of the Golden Era is filled with stock brands, cattle marks, ranch notices, and other livestock topics. This context is important. The word “round-up” comes straight from animal management, referring to gathering, controlling, and moving animals. While we can’t say that Chinese residents were literally treated like cattle, what matters is that the newspaper chose animal-management language to describe them.

The word choice could have shaped community attitudes. It invited readers to see anti-Chinese action as community management. When Chinese residents were described in terms of livestock control, sending them away could seem less like rejecting neighbors and more like handling a local problem. The word “round-up” made exclusion sound familiar, practical, and civic.

The sentence makes it clear who has power and who does not. “The citizens of Silver City” take action, while “the Chinese” are simply acted upon. There’s no mention of courts, sheriffs, laws, or trials. The word “git” is blunt and dismissive. Together, “round-up” and “git” make forced removal sound like an ordinary, common-sense action, not a violation of rights.

This sentence takes anti-Chinese hostility and puts it in the language of civic action. Here, “citizens” stand in for the whole town, and Chinese residents are reduced to non-citizens who need to be moved out of the way.

## A Newspaper That Could Tell Fuller Stories

The Golden Era knew how to tell detailed human stories. In the same issue, a report from Tularosa, named Tiburcio Duran and Anastasio Delphin, described them as “two old friends,” explained their fight, detailed wounds, mentioned the constable, and reported an armed guard around town.³ That story gives names, relationships, sequence, injury, law, and community tension.

The Silver City notice gives a very different record. It omits Chinese names, work, homes, fears, property, injuries, resistance, and destination. It seems clear in the newspaper: some people receive narrative detail, but when speaking of the Chinese, they are reduced to a racial category.

<figure class="image-card">
  <img src="Images/lee_chin.jpg" alt="Lee Chin cabinet card photograph from Las Vegas, New Mexico">
  <figcaption>
    Lee Chin’s ca. 1885 portrait shows a Chinese resident of Las Vegas, New Mexico, presenting himself as part of New Mexican society during the same period of anti-Chinese pressure.
    <cite>Source: Crispell Art Parlor, “Lee Chin, Las Vegas, New Mexico,” ca. 1885, cabinet card photograph, Palace of the Governors Photo Archives, New Mexico History Museum, accessed March 27, 2026.</cite>
  </figcaption>
</figure>

## Deming and Socorro: Labor and Numbers

Other New Mexico newspaper items from 1886 make the Silver City notice more meaningful. On April 20, 1886, the Las Vegas Daily Gazette reported that Deming had recently had an anti-Chinese movement. Now, Deming had “another Chinese laundry.”⁴ This brief item reveals a contradiction. Chinese labor was publicly rejected, yet their laundry work returned.

The wording hides the worker. “Another Chinese laundry” might mean a laundryman stayed, a new one arrived, or workers were seen as interchangeable. The problem and the labor were visible, while the person behind it was hidden.

Five days later, the Gazette reported: “In two months, Socorro reduced her Chinese census from seventy-five to twenty-four.”⁵ This item comes from Socorro, not Deming. It gives a number, not names, and leaves the causes of departure unexplained. Still, the wording is revealing. Chinese residents become a “census,” a count to be lowered.

Silver City, Deming, and Socorro show similar patterns in newspaper coverage. Newspapers represented Chinese people as groups to be expelled, as workers in laundry roles, or as diminished population figures. These portrayals failed to represent the complexity of Chinese life in New Mexico. They illustrate how newspapers acknowledged the Chinese presence while limiting readers’ view of Chinese individuals.

## Protection and Testimony

The Sierra County Advocate, published January 23, 1886, complicates the picture. It criticized anti-Chinese boycotters. The paper reported that in Raton, boycotters targeted those who “support and protect” Chinese people.⁶ Anti-Chinese pressure reached beyond Chinese residents to affect employers, customers, defenders, and protectors.

The same issue reported that anti-Chinese organizing in Central City may have aimed to remove two Chinese witnesses in a murder case involving three murdered Chinese men.⁷ This should be treated carefully as a newspaper claim, not a complete legal record. Even so, it suggests tension in the possibility of Chinese residents becoming significant under the law. Their presence could affect whether the legal truth was heard, and it was unwelcome.

John R. Wunder’s study of Territory of New Mexico v. Yee Shun examines Chinese legal relationships and their rights to testify in territorial New Mexico.⁸ The tension is clear. Chinese people could enter the legal system, yet public pressure threatened their protection, movement, and voice.

## New Mexico in the Wider West

Beth Lew-Williams’s The Chinese Must Go helps place these New Mexico sources in a wider Western context. Lew-Williams argues that the mid-1880s saw widespread anti-Chinese expulsions across the U.S. West. Violence included intimidation, harassment, deadlines to leave, coerced departure, and boycotts. It also went as far as physical assault and murder.⁹ Her appendix identifies Silver City and Raton among hotspots connected to anti-Chinese expulsions or attempted expulsions.¹⁰

While the Golden Era notice omits many details from Silver City, Lew-Williams explains why expressions such as “round-up,” “git,” “anti-Chinese movement,” and “boycott” may have been used through 1885 and 1886. These terms were part of a wider moment across the West when communities pushed the boundary on how far they could go in forcing Chinese people out.

New Mexico was part of this history of exclusion. The Silver City notice is a single public and published example within a larger pattern.

## Recovering People from the Category

The newspapers often failed to name Chinese residents. Karen Leong’s work on Chinese people in Silver City and Grant County explains why that absence matters. Chinese history in New Mexico often survives via fragmented records, inconsistent names, census gaps, business traces, tax records, and documents created by outsiders.¹¹ Newspaper labels like “the Chinese,” “Chinese laundry,” and “Chinese census” preserve evidence of presence. At the same time, they hide individual lives.

Garland D. Bills’ article on Tom Ying offers a story of perseverance among the Chinese. Ying became a long-term Chinese New Mexican resident and restaurant operator, though even his name, age, and early life are difficult to reconstruct.¹² Tom Ying may not have directly faced a circumstance, for example, being “rounded up,” but his importance is different: his life shows a piece of what the phrase “the Chinese” conceals: the names, businesses, movements, uncertainties, and perseverance.

<figure class="image-card">
  <img src="Images/tom_ying.png" alt="Portrait of Tom Ying">
  <figcaption>
    Tom Ying’s portrait gives this project a named Chinese New Mexican life behind the public category “the Chinese.”
    <cite>Source: Reproduced in Garland D. Bills, “Tom Ying: The Hard Life of an Early Chinese Immigrant in New Mexico,” <em>La Crónica de Nuevo México</em>, no. 119 (Fall 2023): 3.</cite>
  </figcaption>
</figure>

## Conclusion

The December 1885 Silver City notice is a critical historical source because it illustrates the importance of language in shaping anti-Chinese exclusion and in the overall AANHPI history in the United States. The terms “citizens,” “round-up,” and “git” clarify who holds power, who is targeted, and how expulsion was normalized. These words demonstrate how the notice functioned to legitimize civic exclusion and re-normalize Chinese residents as a problem to be removed.

The other sources add context to that sentence, even though they don’t fill in all the gaps. Deming shows that Chinese labor was visible, but workers went unnamed. Socorro shows the Chinese population being counted down. Raton shows that even protecting Chinese residents was controversial. Central City hints that Chinese testimony in court was at risk. Leong and Bills both show how hard it is to recover the stories of individual Chinese people from records that mostly preserve categories rather than lives.

This matters for AANHPI history because it helps recover Chinese New Mexicans from a public record that usually reduced them to racial labels, job types, or numbers. It matters for New Mexico history because it ties together town life, newspapers, labor disputes, law, and racial exclusion. The Golden Era’s command was “git.” But the sources that remain show something more: Chinese New Mexicans were already part of New Mexico’s legal, economic, and social life. Trying to force removal was an attempt to reverse just how much they already belonged.

## Bibliography

### Primary Sources

Golden Era (Lincoln, NM). December 3, 1885.

Las Vegas Daily Gazette (Las Vegas, NM). April 20, 1886.

Las Vegas Daily Gazette (Las Vegas, NM). April 25, 1886.

Sierra County Advocate (Hillsborough, NM). January 23, 1886.

### Secondary Sources

Bills, Garland D. “Tom Ying: The Hard Life of an Early Chinese Immigrant in New Mexico.” La Crónica de Nuevo México, Fall 2023.

Leong, Karen J. Chapter in Unpacking Silver City, 103–166.

Lew-Williams, Beth. The Chinese Must Go: Violence, Exclusion, and the Making of the Alien in America. Cambridge, MA: Harvard University Press, 2018.

### Visual Sources

Crispell Art Parlor. “Lee Chin, Las Vegas, New Mexico.” ca. 1885. Cabinet card photograph. Palace of the Governors Photo Archives, New Mexico History Museum. Accessed March 27, 2026. 


Tom Ying portrait. Reproduced in Garland D. Bills, “Tom Ying: The Hard Life of an Early Chinese Immigrant in New Mexico,” La Crónica de Nuevo México, no. 119 (Fall 2023): 3. 