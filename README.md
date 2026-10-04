# Zomato Lite

A lightweight restaurant discovery and review platform exploring a simple question:

**How do you make ratings actually useful when someone is deciding what to eat?**

**Live:** 

---

## Why I built this

Restaurant apps are interesting to me because they're really **decision-making products**.

You open one because you want to eat something.

Then you start comparing restaurants, ratings, reviews, dishes, prices, and trying to figure out what is actually worth ordering.

That made me curious about something:

**What makes a rating trustworthy enough to actually help someone decide?**

So I built a smaller version of that experience.

The goal wasn't to recreate Zomato.

It was to explore the product decisions underneath it:

**What should be rated?
What should be shown?
And how do you make sure the information is actually trustworthy?**

---

## What I built

Zomato Lite lets users discover restaurants, browse menus, and leave structured reviews.

Users can rate:

* The restaurant overall
* Food
* Packaging
* Whether they'd recommend it
* A specific dish

I particularly liked the idea of **dish-level feedback**.

A restaurant might have a great overall rating, but that doesn't necessarily mean the dish you're about to order is good.

So the product goes a little deeper than one overall number.

---

## The idea behind it

A rating like **4.3 ⭐** looks objective.

But where did it come from?

Is it current?

Does it actually match the reviews?

For this project, I deliberately chose to **store the underlying reviews and calculate ratings from them**, rather than storing a separate average.

So when a review is submitted, the rating and review count update from the same source of truth.

**The number the user sees should match reality.**

---

## What I learned

This project made me realise that some of the most important UX decisions aren't visual.

They're about **trust.**

A stale rating, incorrect review count, or confusing filter might seem like a small bug.

But when someone is using your product to make a decision, those small inconsistencies can make the whole product feel unreliable.

It also reinforced something I'm learning about Product Management:

**Small technical decisions can become important product decisions.**

---

## What I'd improve

If I continued building it, I'd explore:

* Personalised restaurant recommendations
* Saved restaurants and lists
* Better dish-level insights
* Review moderation
* User accounts
* More useful discovery

Eventually, I'd want to move beyond:

**"What's highly rated?"**

to:

**"What's actually a good choice for me?"**

---

## Why this project matters to me

I didn't build this because the world needs another restaurant app.

I built it because everyday products are full of interesting decisions hiding in plain sight.

A rating.

A review.

A filter.

A recommendation.

They're simple on the surface, but underneath are questions about **users, trust, data, and behaviour.**

That's the kind of product thinking I want to get better at.

---

## Tech

`Next.js` · `TypeScript` · `Tailwind CSS` · `Neon Postgres` · `SQL` · `Vercel`

Built as a small experiment in **product thinking, data integrity, and building things people can actually use.**
