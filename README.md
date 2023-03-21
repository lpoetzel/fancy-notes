# Fancy React Notes App

This is a responsive React notes app that allows users to create, edit, and delete notes.

Users can also add and manage tags for their notes.

You can then filter by Title and/or Tags and click on the Note so you get directed to the full Note.

The body of the Note has inbuild Markdown support!

Everything is saved to your local storage.

# Demo 
https://fancy-notes-pi.vercel.app/

## Technologies/dependencies
    React
    Typescript
    React Router
    React Markdown
    React Select
    Bootstrap
    uuid
    
## Hooks

    useLocalStorage: Custom hook to persist data in local storage
    useMemo: Hook to memoize expensive calculations
    useState: Hook to add state to functional components.
    useNavigate: Hook to programmatically navigate between pages in a React Router application.

## Setup

To run the app locally, follow these steps:
Clone the repository:

    git clone https://github.com/lpoetzel/fancy-notes.git


Navigate to the project directory:

    cd fancy-notes

Install dependencies:

    npm install

Start the development server:

    npm run dev

## Usage

The app has three main pages:

  Home page (/): Displays a list of notes with their titles and tags.
  
  New note page (/new): Allows users to create a new note by entering a title, markdown content, and selecting tags from a list of available tags.
  
  Note detail page (/:id): Displays the details of a selected note. Users can edit the note or delete it from this page.
  
 <div>
<img src="https://user-images.githubusercontent.com/104060521/220886460-1549c8d1-3295-42b8-bee1-7ef23f9a7362.png" alt="Home view with all notes" width="400" />

<img src="https://user-images.githubusercontent.com/104060521/220886546-6c03070f-ae47-42ce-a21c-03b7ccb7f712.png" alt="single note view" width="400" />

<img src="https://user-images.githubusercontent.com/104060521/220886661-19f3f44a-1e1b-4e22-b705-7a9e406555c7.png" alt="edit note view" width="400" />

<img src="https://user-images.githubusercontent.com/104060521/220887737-375103c5-c2c3-4b27-84f2-96c766fee03f.png" alt="Edit Tags page" width="400" />

</div>
