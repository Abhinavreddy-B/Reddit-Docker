# DASS Assignment 1

## Name: *Abhinav Reddy Boddu*

## Roll No: *2021101034*

# Submissions:

## Bonus:

| Name                         | Status |
| ---------------------------- | :----: |
| Google/Facebook OAuth        |   ❌   |
| CAS Login                    |   ❌   |
| Images for Subgreddit        |   ✅   |
| Stats Graphs                 |   ✅   |
| Email to Reporter            |   ✅   |
| Email to Reported User       |   ✅   |
| Fuzzy Search                 |   ✅   |
| Multi Sort                   |   ❌   |
| Chat                         |   ✅   |
| Confirming to go back        |   ❌   |
| Infinite Loading             |   ✅   |
| Multi-level Comments/Replies |   ✅   |
| Keyboard Shortcuts           |   ✅   |

## Routes

* `/profile` - Profile Page
* `/mysubgreddits` - My SubGreddits Page
* `/manage/:id` - Single SubGreddit Page (From My SubGreddits Page)
* `/subgreddits` - All SubGreddits Page
* `/subgreddit/:id` - Single SubGreddit Page (From All SubGreddits Page)
* `/saved` - Saved Page

## Assumptions:

### Login/Registration:

* **Not** **verifying** Email with **OTP**/similar stuff , (Email Bonus will only be succesfull if valid email is given)
* Login with **Username** and **Password**
* **No** specific **Homepage ,** **Redirect to Profile** page

### Dashboard:

#### Navbar

NA

#### Profile Page

##### Edit

* **Cannot** edit **Username**

##### Followers/Following

NA

#### My Sub Greddiits Page

##### Create New

* Image Upload Done ✅ [**BONUS**]

##### List of Owned subgreddits

* No of people Includes Blocked Users

#### SubGreddit Page (From My SubGreddits)

##### Users (Shortcut Key U)

* First Blocked users, then Unblocked Users (**distinguised by chips beside them**)

##### Join Requests (Shortcut Key J)

NA

##### Stats (Shortcut Key S)

* Stats are shown daywise , from the creation date of subgreddits
* Note this cannot be changed to hourwise, .. etc (Since current implementation does not support) (Not mentioned in PDF)
* Charts [**BONUS**] ✅

##### Reports (Shortcut Key R)

* Block actually Blocks but Mod can still Delete the post (Even after blocking User)
* Email [**BONUS**] ✅

#### All SubGreddits Page

* All Subgreddits **joined** by the User **appear first. Later Others appear.** **Sorting works internally in each seperately. Like Joined are sorted internally, and not joined are sorted internally**
* **All available tags are shown as chips**, Where one can Pick multiple Chips

#### Single SubGreddit Page (From All SubGreddit Page)

* If no image is available , Reddit Logo appears.
* Multi Level Commenting [**BONUS**]
* User can Follow Even a Blocked User (Design Choise I made) (Can be changed with 1/2 lines change in Backend)

### Banned Keywords

NA
