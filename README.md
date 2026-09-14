# Project Proposal

# DormShare

### *Need it? Rent it. Have it? Earn from it.*

## What and why?

DormShare is a mobile web application that creates a trusted, peer-to-peer rental marketplace exclusively for NYU students.

College students often own useful items that spend most of their time unused: projectors, cameras, speakers, calculators, gaming equipment, sports gear, tools, kitchen appliances, monitors, event equipment, and other everyday belongings. At the same time, another student living only a few floors or blocks away may need that exact item for a few hours, a weekend, or a single assignment.

Buying something for such a short-term need can be unnecessarily expensive and wasteful. Meanwhile, the student who already owns the item has no simple way to earn money from it.

DormShare connects these two students.

An owner can turn an underused belonging into a source of extra income by listing it for rent. A renter can gain temporary access to an item for much less than the cost of purchasing it. Because the platform would initially be limited to verified NYU students, exchanges can also be more local, convenient, and accountable than those arranged through general-purpose online marketplaces.

DormShare focuses specifically on **temporary access rather than permanent ownership**. It is not intended to become another general buying-and-selling marketplace.

For small or inexpensive objects where charging rent would make little sense, DormShare would also offer a lightweight borrowing system. A student who needs a screwdriver for twenty minutes, for example, should not need to buy one or negotiate a full rental transaction.

The overall goal is to turn underused belongings already present within the NYU community into a shared, hyperlocal resource while giving students an easy way to earn and save money.

## For whom?

DormShare is designed initially for **NYU students with verified `nyu.edu` email addresses**.

Our first users would be students living in NYU residence halls and students who regularly spend time around NYU's New York campus. These students live and study near one another, which makes short-term exchanges practical.

A DormShare user can act as both an owner and a renter.

An **owner** has an item they do not use frequently and would like to earn money by making it temporarily available to another student.

A **renter** needs temporary access to an item and would prefer to rent it locally rather than purchase it.

Students who need a low-value item only briefly could instead use DormShare's Quick Borrow feature.

Because NYU students are our actual initial users, we would be able to speak directly with potential users throughout development, test prototypes, collect feedback, and refine the product based on real student behavior rather than hypothetical customers.

## How?

DormShare would support four primary actions:

* **Find something** that another student has already listed.
* **Request something** that is not currently available.
* **Quick Borrow** a small or inexpensive item for a short period.
* **List an item** and earn money by renting it to another student.

### Account verification and trust

Users would create an account using an NYU email address and verify their NYU affiliation before participating in the marketplace.

DormShare would use this verified NYU identity as an important layer of accountability. The initial product would not require renters to provide large cash security deposits, since requiring students to lock up additional money could make the service inaccessible.

Instead, trust would come from a combination of:

* verified NYU affiliation
* completed transaction history
* ratings and reviews
* agreed rental terms
* in-app communication
* QR handoff records
* condition photos where appropriate

DormShare would not need to publicly expose sensitive student information such as ID numbers, dorm room numbers, phone numbers, or private addresses.

### Listing an item

An owner could create a listing with:

* item name and category
* photos
* description
* current condition
* rental price
* availability
* approximate pickup area
* included accessories
* relevant rental conditions

For example, a student with a projector that sits unused most of the month could list it for $8 per day.

Owners could pause a listing when they need the item themselves and reactivate it later.

Once an item has an accepted rental for a particular period, DormShare would prevent conflicting bookings for the same dates.

### Finding an item

Students could browse or search available listings and view information such as:

* price
* owner rating
* item condition
* availability
* approximate location
* completed rental history

The first version would prioritize straightforward search and browsing rather than attempting to build a highly advanced availability-based search engine.

### Requesting an unavailable item

If the desired item is not currently listed, a student could create an **Item Request**.

The request could specify:

* what they need
* when they need it
* how long they need it
* an optional target price

Other students could browse requests and respond if they own the requested item.

For example:

> **Looking for:** Portable projector
> **Need it:** Friday evening through Saturday morning
> **Target price:** Around $10

A student who owns a projector but had never thought about listing it could respond directly.

This allows DormShare to work in both directions: owners can create supply, and renters can create demand.

A future version could notify users when a newly created listing appears to match one of their previous requests.

### Quick Borrow

Some exchanges do not make sense as paid rentals.

A screwdriver that costs approximately $10, for example, might only be needed for twenty minutes. Charging a meaningful rental price would create more friction than value.

DormShare would therefore offer a separate **Quick Borrow** flow for inexpensive items needed briefly.

A request might say:

> Need a Phillips screwdriver near Third North for about 20 minutes.

Another student could offer to lend the item for free or for a small optional amount.

An owner could choose whether an item is:

* available for rent
* available to borrow
* available for both

Keeping borrowing separate from normal rentals allows DormShare to support casual student-to-student sharing without weakening its main rental marketplace.

### Private in-app chat

When two users interact through a listing or request, DormShare would provide a private in-app conversation.

Similar to Airbnb, communication would remain within the platform so users would not need to expose personal phone numbers.

Users could use chat to:

* ask questions about an item
* clarify condition
* negotiate price
* discuss rental duration
* arrange pickup
* coordinate return
* request an extension

Keeping communication inside DormShare also provides a record of what was discussed if a disagreement occurs later.

### Negotiation

Owners could either set a fixed rate or allow offers.

For example:

> Listed price: $10/day

A renter might offer:

> $18 for the weekend

The owner could accept, reject, or counter the offer.

Once both sides agree, the final terms would be recorded in the booking.

### Rental Summary and agreement

Before the rental is confirmed, both users would see a shared **Rental Summary**.

For example:

**Item:** Portable projector
**Rental period:** Friday 6 PM – Sunday 6 PM
**Agreed price:** $18
**Pickup area:** Third North lobby
**Condition:** Good
**Included accessories:** Charger, HDMI cable, carrying case
**Late-return policy:** Displayed before confirmation

Both users would confirm the same terms before the booking becomes active.

The rental agreement would establish expectations around:

* rental duration
* agreed price
* item condition
* expected use
* included accessories
* cancellation
* extensions
* late returns
* damage or loss
* no-shows
* return expectations

The exact contractual language and policies could be refined as the product is developed.

### Payment

DormShare would **not process or hold payments in the initial version**.

The application would record the agreed rental price, but the owner and renter would handle payment outside the platform using whatever payment method they mutually prefer.

This keeps the semester project focused on solving the rental and trust workflow rather than introducing the additional complexity of financial processing, refunds, chargebacks, payment compliance, and payouts.

Integrated payments could be considered in a future version.

### Pickup and QR check-in

Once a rental is accepted, the two students would arrange a pickup through the private chat.

DormShare would generate a unique QR code associated with the transaction.

When the students meet, the code could be scanned to confirm that the item physically changed hands.

The rental would move through a clear lifecycle:

**Requested → Accepted → Checked Out → Returned → Completed**

The return could use a similar confirmation process.

The QR system creates a simple record of when possession changed hands rather than relying only on either user's word.

### Item condition and accessories

For items where condition matters, users could upload photos at pickup and again at return.

Owners could also specify the accessories included with an item.

For example:

**Camera rental includes:**

* camera body
* battery
* charger
* SD card
* carrying case

This helps avoid disagreements about whether something was already damaged or whether an accessory was returned.

Condition photos, included-item lists, rental terms, and chat records could all become useful if a dispute occurs.

### Rental extensions

If a renter needs an item for longer than originally agreed, they could submit an **extension request**.

The owner could approve or reject the extension.

The system would also make sure the extension does not conflict with another confirmed rental.

If approved, the new duration and any adjusted price would become part of the transaction record.

### Cancellation and no-shows

DormShare would establish clear cancellation expectations before a rental begins.

The system could distinguish between:

* early cancellation
* last-minute cancellation
* owner cancellation
* renter cancellation
* no-show

A no-show would not necessarily require a complicated financial penalty, especially because payments occur outside the platform.

Instead, repeated no-shows could negatively affect a user's reputation through ratings and reviews.

This gives users an incentive to communicate and respect agreed pickup times.

### Late returns

The agreed rental terms would include a late-return policy.

Owners and renters would know those expectations before confirming the booking.

A renter who realizes they cannot return an item on time would be encouraged to request an extension rather than simply keeping the item beyond the agreed period.

Repeated late returns could also be reflected in ratings and transaction history.

### Two-way rating system

After a completed transaction, both participants would review each other.

The renter could rate:

* whether the item matched its description
* communication
* pickup experience
* overall experience

The owner could rate:

* communication
* punctuality
* treatment of the item
* overall experience

Only users who actually participated in a completed transaction would be allowed to leave reviews.

To reduce retaliatory ratings, DormShare would follow an Airbnb-style two-way review system. Neither user would see the other's review until both have submitted one or until the review period expires.

A user's profile could eventually display:

* average rating
* number of completed rentals
* written reviews
* successful transaction history

This gives users more context than a star rating alone.

### Notifications

DormShare could notify users when important events occur, including:

* new rental request
* new message
* offer received
* offer accepted or rejected
* booking confirmed
* upcoming pickup
* upcoming return
* extension request
* overdue rental
* response to an Item Request
* response to a Quick Borrow request

### Earnings and rental history

Owners would have a dashboard showing:

* active listings
* upcoming rentals
* completed rentals
* total recorded earnings
* frequently rented items

Renters could view:

* active rentals
* upcoming returns
* previous rentals
* Item Requests
* Quick Borrow requests
* saved items

Because payments take place externally, the earnings dashboard would reflect the rental prices recorded through completed DormShare transactions rather than money actually processed by DormShare.

### Privacy and pickup safety

DormShare would avoid publicly exposing precise private locations.

A public listing might display:

> Near Third North

rather than:

> Room 812

After a booking is accepted, users could arrange a more specific pickup point through private chat.

The platform could encourage exchanges in public or shared spaces such as residence hall lobbies or campus locations rather than private rooms.

### Prohibited items

DormShare would maintain rules defining what may and may not be listed.

Suitable categories could include:

* electronics
* school supplies
* tools
* sports equipment
* event equipment
* games
* household items
* certain kitchen items

Unsafe, illegal, age-restricted, controlled, medical, stolen, or otherwise inappropriate goods would be prohibited.

Users could report questionable listings for moderator review.

### Reporting and moderation

Users could report:

* prohibited listings
* misleading descriptions
* harassment
* no-shows
* damage
* missing items
* abusive behavior
* repeated policy violations

Administrators would have basic moderation tools to:

* review reports
* remove prohibited listings
* warn users
* restrict accounts
* remove repeat offenders

### Damage and disputes

The rental agreement would define user responsibilities for damage, loss, and return condition.

If a disagreement occurs, a user could report the transaction and provide relevant information.

DormShare could retain records associated with the transaction, including:

* agreed terms
* timestamps
* in-app messages
* QR handoff confirmations
* condition photos
* accessory lists
* reviews

The exact resolution rules for damage and other disputes would be refined as the application's policies are developed.

DormShare would not attempt to replace existing university or legal authorities.

Serious situations involving theft, threats, personal safety, or similar concerns could direct users toward appropriate NYU Public Safety, university reporting, or emergency channels.

A formal integration or partnership with NYU Public Safety would only be represented if such a relationship were actually established.

## Scope

DormShare is appropriately scoped for a team of approximately 4–6 developers working over one semester.

The application contains multiple substantial but connected areas of functionality:

**NYU account verification → profiles and reputation → listings → search → Item Requests → Quick Borrow → availability → private chat → negotiation → bookings → rental agreements → QR handoffs → rental tracking → extensions → cancellations → ratings → transaction history → reporting and moderation**

These features provide enough work to divide responsibilities across a development team and allow the product to evolve incrementally through multiple Agile sprints.

At the same time, DormShare would deliberately avoid several features that could make the semester project unnecessarily ambitious.

The initial version would not require:

* integrated payment processing
* cash security deposits
* delivery services
* insurance
* standalone buying and selling
* advanced identity verification beyond NYU affiliation
* automated dispute resolution
* highly sophisticated availability search
* auctions or bidding
* formal integration with NYU Public Safety
* complex financial or legal infrastructure

A successful first version should support the complete core journey:

**List or request an item → find another student → communicate → agree on terms → confirm the booking → exchange the item → return it → review the transaction.**

Additional features can be introduced after this core workflow is reliable.

## Product vision

A successful DormShare interaction might look like this:

A student realizes on Friday afternoon that they need a projector for an event that evening.

They open DormShare and search available listings. Nothing suitable is currently listed, so they post an Item Request explaining that they need a projector for the weekend.

Another verified NYU student owns one but had never considered renting it out. They respond to the request.

The two students communicate through DormShare without exchanging phone numbers. They discuss the projector, negotiate an $18 weekend price, agree to meet in a residence hall lobby, and confirm the Rental Summary.

At pickup, they document the projector's condition and accessories and scan the rental QR code to confirm the handoff.

The renter later realizes they need the projector for several additional hours and submits an extension request. The owner approves it.

When the projector is returned, the users confirm the return and each submits a private review. After both reviews are complete, the ratings become visible on their profiles.

The renter avoided purchasing an expensive item for one event.

The owner earned money from something that would otherwise have remained unused.

That is the experience DormShare is designed to make routine.

**Need it? Rent it. Have it? Earn from it.**


## Collaboration / Team members

* [Omer Hayat](https://github.com/OmerNYU)
* [Hassan Raza](https://github.com/hassanraza04)
* [Muhammad Sheharyar Ullah Khan](https://github.com/SherryKhanW)
* [Siraj Mohamed Hanzalah](https://github.com/hanza-siraj)
