# Project Proposal
### Project title
BuyNearby (or something similar, open for ideas 🙂)

### What and why?
You wake up in the morning in your newly furnished dorm room, go to the kitchen, grab a piece of bread dreaming about that _tasty toast with butter_, and... And you realize that you do not have a toaster (for this story, let's assume that you don't have a pan either). Luckily, you have a smartphone with a browser, so you navigate to the BuyNearby website, find a used toaster that is sold for $2 (holy!) and is less than a mile away! A recent graduate downstairs owned it, so you just run down, hand them a couple of bucks, and voilà! BuyNearby just saved your morning (and probably the rest of the mornings this semester).

BuyNearby is an online marketplace that helps you to find used home appliances and furniture nearby.

The platform would solve the following issues:
- Completely fine and usable furniture or home appliances thrown out in the streets of New York
- Overpriced vacuum cleaners, microwaves, yada yada
- No need to take that J train to the closest Target... just walk outside and pick-up the toaster from your neighbour
- ...
- Global warming (contribution to the "greener" society - second-hand markets extend the lifetime of electronics and hardly recycable items)

### For whom?
Such platform would be perfect for students, but also for humble New Yorkers. Well suited for densely populated cities like New York.

### How?
#### Listing
The listing should have all the necessary information to the buyer, such as the title/name of the listing, description, category, price, approximate distance from the potential buyer, condition.

#### Users
All users should have profiles (for legitimacy purposes) with ratings from sellers/buyers, brief description, verification status (maybe phone number verification or university email verification if we primarily target students on-campus).

#### Core functionality
Users should be able to login/logout (auth), explore listings conveniently, post listings, edit and delete their previous listings, write reviews/ratings for other users, contact other users via platform, receive notifications via email or inner notification system, report listings/users.

#### Happy flow
Potential client lands in the home page, which contains a list of the most recent listings (closest appearing first). Each listing includes brief information about it like thumbnail picture, distance from the buyer, price, short description, item's category, link to the author's profile, 'buy' button. There is also an interactive map on the side, showing the approximate locations of all the recent listings. The potential client browses the listings, scrolls down the infinite scroll, types some keywords in the search bar, adds price, distance, and category filters. They then press the buy button, log in to the website, and send an auto-generated message to the seller of the desired listing. The seller receives email/phone notification, navigates to the website, and both parties decide on the logistics via the inner messaging platform.

There are a lot of potential features that could be added in the future, such as authorized payments, courrier/last-mile delivery options, recent listing results based on the latest user searches, integrations with local stores.

### Scope
This project is a simple CRUD (Create-Read-Update-Delete) application with some complementary services (like messaging, notifications). I believe that the CRUD part is most certainly doable, the additional functionality may be more challenging to implement within the given timeframe, but I don't think it's impossible either.
