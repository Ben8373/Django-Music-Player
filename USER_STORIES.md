# Django Music Player - User Stories & Project Planning

## Table of Contents
1. [All User Stories](#all-user-stories)
2. [MoSCoW Prioritization](#moscow-prioritization)
3. [Must Have - Acceptance Criteria (Beginner-Friendly)](#must-have-acceptance-criteria)
4. [Site Owner - 4 Essential Stories](#site-owner-essential-stories)

---

## All User Stories

### Site User Stories

#### Music Playback
- As a **site user**, I want to **browse available songs** so that I can **discover music to listen to**
- As a **site user**, I want to **play, pause, and stop songs** so that I can **control my listening experience**
- As a **site user**, I want to **adjust the volume** so that I can **listen at my preferred sound level**
- As a **site user**, I want to **see the current playback progress** so that I can **know how much of the song has played**
- As a **site user**, I want to **skip to the next or previous track** so that I can **navigate through my playlist**

#### Playlists & Organization
- As a **site user**, I want to **create custom playlists** so that I can **organize my favorite songs**
- As a **site user**, I want to **add songs to my playlists** so that I can **build collections of music**
- As a **site user**, I want to **search for songs by title, artist, or album** so that I can **quickly find specific music**
- As a **site user**, I want to **filter songs by genre** so that I can **discover music matching my mood**

#### User Account
- As a **site user**, I want to **create an account** so that I can **save my preferences and playlists**
- As a **site user**, I want to **log in and out** so that I can **access my personalized content securely**
- As a **site user**, I want to **view my listening history** so that I can **replay songs I've enjoyed**
- As a **site user**, I want to **mark songs as favorites** so that I can **quickly access my preferred tracks**

### Site Owner Stories

#### Content Management
- As a **site owner**, I want to **upload new songs to the platform** so that I can **expand the music library**
- As a **site owner**, I want to **edit song metadata (title, artist, album, genre)** so that I can **maintain accurate information**
- As a **site owner**, I want to **delete songs from the library** so that I can **remove inappropriate or copyrighted content**
- As a **site owner**, I want to **organize songs into categories** so that I can **help users discover music**

#### User Management
- As a **site owner**, I want to **view registered users** so that I can **monitor platform growth**
- As a **site owner**, I want to **manage user permissions** so that I can **control access to features**
- As a **site owner**, I want to **ban problematic users** so that I can **maintain a safe environment**

#### Analytics & Monitoring
- As a **site owner**, I want to **view playback statistics** so that I can **understand which songs are popular**
- As a **site owner**, I want to **monitor storage usage** so that I can **manage server resources**
- As a **site owner**, I want to **receive error notifications** so that I can **quickly address technical issues**

#### Administration
- As a **site owner**, I want to **access the Django admin panel** so that I can **manage the database directly**
- As a **site owner**, I want to **backup the database** so that I can **prevent data loss**
- As a **site owner**, I want to **configure site settings** so that I can **customize the platform behavior**

---

## MoSCoW Prioritization

### **MUST HAVE** (Critical for MVP)

#### Site User
- As a **site user**, I want to **browse available songs** so that I can **discover music to listen to**
- As a **site user**, I want to **play, pause, and stop songs** so that I can **control my listening experience**
- As a **site user**, I want to **create an account** so that I can **save my preferences and playlists**
- As a **site user**, I want to **log in and out** so that I can **access my personalized content securely**

#### Site Owner
- As a **site owner**, I want to **upload new songs to the platform** so that I can **expand the music library**
- As a **site owner**, I want to **edit song metadata (title, artist, album, genre)** so that I can **maintain accurate information**
- As a **site owner**, I want to **delete songs from the library** so that I can **remove inappropriate or copyrighted content**
- As a **site owner**, I want to **access the Django admin panel** so that I can **manage the database directly**

---

### **SHOULD HAVE** (Important but not critical)

#### Site User
- As a **site user**, I want to **adjust the volume** so that I can **listen at my preferred sound level**
- As a **site user**, I want to **see the current playback progress** so that I can **know how much of the song has played**
- As a **site user**, I want to **skip to the next or previous track** so that I can **navigate through my playlist**
- As a **site user**, I want to **search for songs by title, artist, or album** so that I can **quickly find specific music**
- As a **site user**, I want to **create custom playlists** so that I can **organize my favorite songs**
- As a **site user**, I want to **add songs to my playlists** so that I can **build collections of music**

#### Site Owner
- As a **site owner**, I want to **view registered users** so that I can **monitor platform growth**
- As a **site owner**, I want to **organize songs into categories** so that I can **help users discover music**

---

### **COULD HAVE** (Desirable enhancements)

#### Site User
- As a **site user**, I want to **mark songs as favorites** so that I can **quickly access my preferred tracks**
- As a **site user**, I want to **view my listening history** so that I can **replay songs I've enjoyed**
- As a **site user**, I want to **filter songs by genre** so that I can **discover music matching my mood**

#### Site Owner
- As a **site owner**, I want to **view playback statistics** so that I can **understand which songs are popular**
- As a **site owner**, I want to **manage user permissions** so that I can **control access to features**
- As a **site owner**, I want to **ban problematic users** so that I can **maintain a safe environment**

---

### **WON'T HAVE** (Not in initial release)

#### Site Owner
- As a **site owner**, I want to **monitor storage usage** so that I can **manage server resources**
- As a **site owner**, I want to **receive error notifications** so that I can **quickly address technical issues**
- As a **site owner**, I want to **backup the database** so that I can **prevent data loss** *(can be handled manually/externally)*
- As a **site owner**, I want to **configure site settings** so that I can **customize the platform behavior** *(use Django settings directly)*

---

## Must Have - Acceptance Criteria

### Site User Stories

#### 1. Browse Available Songs
**User Story:** As a site user, I want to browse available songs so that I can discover music to listen to

**Acceptance Criteria:**
- ✓ I can see a list of all songs on the library page
- ✓ Each song shows: title, artist, and album
- ✓ If no songs exist, show message "No songs available"

---

#### 2. Play, Pause, and Stop Songs
**User Story:** As a site user, I want to play, pause, and stop songs so that I can control my listening experience

**Acceptance Criteria:**
- ✓ Clicking "Play" starts the song
- ✓ Clicking "Pause" pauses the song
- ✓ Clicking "Play" again continues from where it paused
- ✓ I can see which song is currently playing

---

#### 3. Create an Account
**User Story:** As a site user, I want to create an account so that I can save my preferences and playlists

**Acceptance Criteria:**
- ✓ I can enter username, email, and password to register
- ✓ Username must be unique
- ✓ Password must be at least 8 characters
- ✓ After successful registration, I see a confirmation message

---

#### 4. Log In and Out
**User Story:** As a site user, I want to log in and out so that I can access my personalized content securely

**Acceptance Criteria:**
- ✓ I can log in with my username and password
- ✓ After login, I see my username displayed on the page
- ✓ I can click a "Logout" button to log out
- ✓ After logout, I'm redirected to the home page

---

### Site Owner Stories

#### 5. Upload New Songs
**User Story:** As a site owner, I want to upload new songs to the platform so that I can expand the music library

**Acceptance Criteria:**
- ✓ I can select an audio file (MP3 format) from my computer
- ✓ I can enter song title, artist, and album name
- ✓ After upload, the song appears in the library
- ✓ I see a success message after uploading

---

#### 6. Edit Song Metadata
**User Story:** As a site owner, I want to edit song metadata so that I can maintain accurate information

**Acceptance Criteria:**
- ✓ I can click "Edit" on any song
- ✓ I can change the title, artist, and album
- ✓ Clicking "Save" updates the song information
- ✓ Updated information shows immediately in the library

---

#### 7. Delete Songs from Library
**User Story:** As a site owner, I want to delete songs from the library so that I can remove inappropriate content

**Acceptance Criteria:**
- ✓ I can click "Delete" on any song
- ✓ A confirmation message asks "Are you sure?"
- ✓ After confirming, the song is removed from the library
- ✓ The song no longer appears in the list

---

#### 8. Access Django Admin Panel
**User Story:** As a site owner, I want to access the Django admin panel so that I can manage the database

**Acceptance Criteria:**
- ✓ I can access the admin panel at `/admin/` URL
- ✓ I can view all songs in the database
- ✓ I can add, edit, or delete songs from the admin panel
- ✓ Only admin users can access this page

---

## Site Owner - Essential Stories

### 1. Add Songs to Library
**User Story:** As a site owner, I want to add new songs so that users have music to listen to

**Acceptance Criteria:**
- ✓ I can upload an MP3 file from my computer
- ✓ I can enter the song title (required)
- ✓ I can enter artist and album (optional)
- ✓ The song appears in the library after upload
- ✓ I see a success message

**What to Build:**
- A simple HTML form with file input and text fields
- A Django view that handles the file upload
- Save the audio file to `media/songs/` folder
- Create a new Song object in the database

---

### 2. Update Song Details
**User Story:** As a site owner, I want to edit song information so that I can fix mistakes

**Acceptance Criteria:**
- ✓ I can click "Edit" on any song
- ✓ I can change the title, artist, or album
- ✓ I click "Save" to update the song
- ✓ Changes appear immediately in the library

**What to Build:**
- An edit page/form that pre-fills with current song data
- A Django view that updates the Song object
- Redirect back to the song list after saving

---

### 3. Remove Unwanted Songs
**User Story:** As a site owner, I want to delete songs so that I can keep the library clean

**Acceptance Criteria:**
- ✓ I can click "Delete" on any song
- ✓ A confirmation asks "Are you sure?"
- ✓ The song is removed after I confirm
- ✓ The song no longer appears in the library

**What to Build:**
- A delete confirmation page showing the song title
- A Django view that deletes the Song object
- Remove the audio file from storage
- Redirect back to the song list

---

### 4. Manage Content via Admin Panel
**User Story:** As a site owner, I want to access the Django admin panel so that I can manage all content easily

**Acceptance Criteria:**
- ✓ I can access admin at `/admin/` URL
- ✓ I can view all songs, users, and playlists
- ✓ I can add, edit, or delete any content
- ✓ Only admin accounts can access this area

**What to Build:**
- Register the Song model in `admin.py`
- Create a superuser account with `python manage.py createsuperuser`
- Configure which fields show in the admin list view

---

## Implementation Guide for Beginners

### Recommended Order
1. **Story #4** (Admin Panel) - Requires minimal code, start here!
2. **Story #1** (Add Songs) - You need songs before anything else
3. **Story #2** (Edit Songs) - Similar to upload, just pre-filled
4. **Story #7** (Delete Songs) - Simplest delete functionality

### Tips
- Start with one story at a time
- Test each criterion manually by using the feature yourself
- Don't worry about edge cases initially - focus on making basic functionality work first
- Once core features work, add validation and error handling
- Use Django's built-in forms to make coding easier
- Start with Django Admin - it's already built into Django!

---

*Last Updated: February 16, 2026*
