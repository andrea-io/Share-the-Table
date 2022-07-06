Share the Table App Design Project - README
===

# Share the Table

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
Share the Table is the new dating app designed for foodies! Users will create a profile about themselves, similar to a dating app, and answer questions about their food preferences. This app will allow users to find other users to "share the table" with and have a meal at a new restaurant, cafe, bar, etc. The user will be able to swipe left or right to match with other users (and their top wishlist for food spots) and message them to set up a time to have a meal.    

### App Evaluation
- **Category:** Social Media
- **Mobile:** Will be centered around a mobile experience, no website. All features are mobile.
- **Story:** Anyone that is a foodie and wants to share an experience of grabbing a meal at a new food spot with others in their area.
- **Market:**
- **Habit:**
- **Scope:**

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* User can create an account
* User can login
* User can create a profile and view their own profile
* User can swipe to match/not match with another user's profile
* User can tap on another user's profile and view a detailed profile view
* User can message another user, if matched with them

**Optional Nice-to-have Stories**

* [fill in your required user stories here]
* ...

### 2. Screen Archetypes

* Login Screen
   * User can login
* Registration Screen
   * User can create an account
   * User can create a profile
* Self Profile Screen
    * User can view their own profile
* Feed Screen
    * User can swipe to match/not match with another user's profile
* Detailed User Profile Screen
    * User can tap on another user's profile and view a detailed profile view
* Conversation Screen
    * User can message another user, if matched with them

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Feed Screen
* Conversation Screen
* Self Profile Screen

**Flow Navigation** (Screen to Screen)

* Login Screen
   => Feed Screen
* Registration Screen
   => Feed Screen
* Feed Screen
   => Conversation Screen
   => Detailed User Profile Screen
   => Self Profile Screen
* Conversation Screen
   => Feed Screen

## Wireframes
Within Repo

## Schema 
### Models
| Property | Type                     | Description                                                  |
|----------|--------------------------|--------------------------------------------------------------|
| objectId | String                   | Unique ID number that corresponds to a user                  |
| user     | Object pointer to a User | User of the profile displayed                                |
| image    | File                     | Main image on a user profile that is first displayed on feed |
| response | String                   | Response to questionaire in initial form                     |
|          |                          |                                                              |

### Networking
- [Add list of network requests by screen ]
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]
