Title: Storage for Orders, Meals Profiles, User Profiles
What:  Should we use async notifications on the orders, meals profies, user profiles? Or we can send change updates via a message bus?
Context: Web site needs to present the current info on order status, meals facts, and details on user profiles. If the customer changes the info, it must be available right away.
Decision: User relational storage for Orders, Meals Profiles, User Profiles. The changes to those entities are not frequent, a MySql or Postrges can handle that. We can possibly have a write-through cache if read performance starts degrading.

