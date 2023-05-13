```mermaid
  classDiagram
    class EssentialFeatures
    class NonEssentialFeatures
    class Entities

    EssentialFeatures: User Signup
    EssentialFeatures: User Login
    EssentialFeatures: User LogOut
    EssentialFeatures: Recommend 
    EssentialFeatures: View recommended

    NonEssentialFeatures: Add contact/s
    NonEssentialFeatures: View/Edit/Delete contact/s
    NonEssentialFeatures: Direct recommend to contact/s
    NonEssentialFeatures: Filter recommended view by category
    NonEssentialFeatures: Comment on recommendations
    NonEssentialFeatures: Upvote/downvote recommendation
    NonEssentialFeatures: See other peoples profile

    Entities: Users
    Entities: Recommends
    Entities: Contacts
```