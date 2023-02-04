# Mark Down Previewer
This project was made as a part of the [DevJam](https://www.devjam.org/) projects. The project requires that the **Mark Down** written in a text area should be able to convert it to structurally valid XHTML (or HTML). The project was written in [Next.js](https://nextjs.org/) for DOM manipulation and SEO purposes.

## Demo
The users can enter Mark Down code on the Code Editor on the left side of the screen. The application will then show the HTML render on the right side of the screen. The user can copy the code via the Copy button on the bottom right side of the screen.

![Demo](/public/demo.gif "Demo")

**Link to the website** : https://livemarkdownpreview.com/

## Project Features
### User Stories

- ✅ User can enter Github flavored markdown into a textarea
- ✅ User can see the resulting HTML in another container/box by pressing on a button
### Bonus Features
- ✅ User can see the resulting HTML updated automatically when the markdown textarea is changed
- ✅ When closing the browser window the markdown formatted text will be stored in localStorage and when the User returns, the data will be retrieved and displayed
- ✅ User can click a button and the content of the box is saved to the clipboard

## Technical
### Dependencies
- Next.js
- React-DOM
- Monaco Editor
- React-icons
### Hosting
The application is hosted on Vercel.

## Development

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.
