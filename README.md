# StudyShelf

A static, browser based study library for three exam subjects. Add your prepared PDFs, ask a question, and see the best matching passage beside a short revision version.

## Enable GitHub Pages

The app is already in the repository root as `index.html`.

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select the `main` branch and `/ (root)`, then save.
4. GitHub will publish the app at `https://tabishsyed777.github.io/Study-Shelf/` after deployment finishes.

## Use

- Rename Subject 1, Subject 2 and Subject 3 to your course names.
- Select a subject and add its PDFs, or choose a subject folder. A folder with the same name as a subject is added to that subject.
- Search a question. StudyShelf ranks matching passages from the PDFs and displays the best passage and a short version for revision.

The short version is made from the opening sentences of the best matching passage. It does not create new content or verify the answer, so compare it with the full passage and your source PDF.

## Data and privacy

PDFs are read and searched in the browser. StudyShelf does not upload them to a server or save them between visits; reload the page and add the PDFs again. PDF.js is loaded from cdnjs to read PDF text, so an internet connection is needed. Search works best with PDFs that contain selectable text; scanned image PDFs need OCR before use.
