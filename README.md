# Physics Computing Centre website

Prototype website for the Department of Physics computing centre at Imperial
College London (working name pending approval).

## Layout

The website files sit at the repository root so GitHub Pages can serve them
directly:

    index.html
    computing-access.html
    research-training.html
    about-people.html
    styles.css
    assets/          images and logos, currently empty
    brief/           the editorial brief (Revision 4), the authoritative
                     source for all wording

Open index.html in a browser to view the site locally, or enable GitHub
Pages (Settings > Pages > Deploy from a branch > main, / root) to publish it.

## Editing rules

- brief/Website_Copy_and_Page_Structure.docx is the authoritative wording.
  Change the brief first, then the site.
- Double-bracketed items, [[APPROVED NAME]], [[SHORT FORM]] and
  [[CENTRE MAILBOX]], are controlled placeholders shown in amber. Replace
  all instances consistently, in the same pass as the job advert. The
  contact link's mailto address (currently REPLACE-ME@imperial.ac.uk) must
  be replaced along with the visible text.
- Other amber items on the pages mark content awaiting confirmation.

## Before launch

- Approve the name and short form; establish the contact mailbox.
- Add the academic lead, technical leads and governance information.
- Obtain service-owner sign-off on the computing descriptions, including
  the list of collaborations named under The Grid Cluster.
- Add at least two approved case studies (Research & Training).
- Confirm or delete the MRes contribution sentence; confirm workshops.
- Confirm the acknowledgement wording.
- Add the Home image, people photographs and partner logos to assets/,
  with alt text for each.
- Set the Page reviewed date on Computing & Access.
- Final implementation is expected in Imperial's web framework (T4);
  complete keyboard, screen-reader and zoom testing there.
