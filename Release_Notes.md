## About Neuro
Neuro empowers CMS enabled website. It is a CMS Adapter that allows centralised management of content for websites, social channels and blogging platforms.
Extremely versatile and simple control UI with easy publishing to multiple environments (live, staging, demo, etc), makes this great for any content management. 

### RELEASES

#### 2024-04-17
- Fixes
  - Allow detaching of media from album
  - For grid views - remember last view size selected
- New Features
  - Enabled global `Albums` feature
  - Enabled `Media Gallery` feature (for direct access to media)
    - Media downloadable
    - Edit media names
    - Delete media (permanent delete from storage)

#### 2023-11-01
Version (v2.0.0) is a major release and is full refactor codebase with support for Media handling 
- Enabled Themed UI
  - Simple and elegant UI full responsive design
- Introduced multi album feature
  - All types of articles can now support multiple albums 
- Global Album viewer
  - with support for media gallery viewing and editing
  - multi language support for media labelling
  - media can be tagged for quick organising and quick searched
- Global Media gallery
  - Search and query all media you house
- Improved navigation
  - List sorting 
  - Disk process notifications
- Tags have been refactored
  - Complete rebuild of tagging
  - Tag can be input changed to Enter key
  - Tag names are normalised to allow space in name and also to avoid duplicates
  - Tag names can be now cased when typing but will be normalised on save 

ToDo::ReleaseTest
- Switch WYSIWYG editor and use rich text headless component under the hood

#### 2023-10-22
- Introduced settings configurator (backend work)
- Release notes now added as notification view 
- Bug fixes:
  - Content editor toolbar stays fixed
#### 2023-10-21
- Framework refactoring to support widgets, menu and settings
- New widgets added: Welcome, Article Tags, Article Types, User Levels
- Bug fixes:
  - removed sequence numbering on media edit
  - allow generating media display name from filename

#### 2023-10-16
- Basic user management
- Dashboard improvements
- Settings and site-wide configurations
- Media can now have true Display name (optional) instead of Filename
- Media original filename is maintained for tracking

#### 2023-10-14
- Introduced basic album feature

#### 2023-10-13
- Moved gallery view to the bottom of article view
- Article Tags are enabled 
  - Can create, edit or delete tags 
  - Multiple tag support
- Dashboard lists used Tags
- Article UI tweaks

#### 2023-10-12
- Remove media filename extension when creating display names from filename
- Added support for wysiwyg editor source view

#### 2023-10-11
- Default Sort: 
  - Articles are ordered by descending order of Article Date
  - Media is ordered by an order index (sequential number) 
- Media display refreshes based on Portrait or Landscape selection
- Media page shows media attribute info (size, mime type etc...)
- Renamed media info column `sort_column` to `sort_index`
- Drag and organise order of media 

#### 2023-10-10
- For each media you can now see the name underneath it 
- All direct edit icons on media are removed to create easier workflow
- Clicking an item in media gallery will simply show it in a popup modal 
- Media Edit option now has additional functionality:
  - Ability to change name of media and write up a description 
  - Set orientation of the image (portrait or landscape)
  - Add media - by drag and drop or browse
  - Select an image to edit name, description and also to delete media

### COMING SOON
- Media album feature for articles
- Article grid view
- List ordering
- Sort media by ascending or descending order

### ROADMAP
- Global Media Gallery
- Media view support
- Testimonials
- Downloads
  - Private (with Key/Secret)
  - Public
- Website Profiles
  - Updates via API Integration
- User Notifications
- When uploading media - give option to opt in or out of creating Display names
