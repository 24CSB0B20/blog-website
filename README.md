# Personal Portfolio

A personal portfolio site built with pure HTML5 and CSS3 for FSD assignment. This started out as
my blog assignment from WP (Web Programming Lab) in first year, which I reconstructed
into a portfolio from the base. All content comes my current resume as of 03/08/2026.


## Design rationale

I wanted it dark and simple, and space themed due to my interests. It's one page with sections stacked
top to bottom: intro, about, projects, skills, experience, and a contact form. All the colours and
spacing are in CSS variables at the top of `style.css`, so changing the whole theme later is a
one minute job. I reused whatever assets made sense from the old assignment and left the rest.
the `link.html` page is now just a full resume overview.

## Layout Justification (Flexbox)

I used Flexbox for everything i.e the nav, the hero, the project cards, the skills chips and the
form. Ever since I learnt web development I've always preferred flexbox over css-grid, and always
use it regardless of the usecase.

## Known limitations

The contact form doesn't submit anywhere, but that's for maybe a future backend assignment.
Due to the limitations of the assignment for not using a framework, CSS classes have become
quite verbose, and DRY isn't really enforced, but it is necessary to meet the assignment
requirements.