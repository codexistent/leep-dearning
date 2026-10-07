---
title: Home
layout: page
---

# Leep Dearning

A collection of deep learning projects/mini projects, each with interactive in-browser demos.

<style>
  .projects { display: grid; grid-template-columns: repeat(auto-fit, minmax(240px, 1fr)); gap: 1rem; margin: 1.5rem 0; }
  .project-card {
    display: block; padding: 1.25rem; border: 1px solid #e5e7eb; border-radius: 12px;
    text-decoration: none; color: inherit; transition: border-color .15s, box-shadow .15s, transform .15s;
  }
  .project-card:hover, .project-card:focus-visible { border-color: #4f6bed; box-shadow: 0 4px 16px rgba(79, 107, 237, .15); transform: translateY(-2px); }
  .project-card .emoji { font-size: 2rem; line-height: 1; }
  .project-card h3 { margin: .6rem 0 .3rem; }
  .project-card p { margin: 0; color: #6b7280; font-size: .95rem; }
</style>

<div class="projects">
  <a class="project-card" href="{{ '/project-panda-grizzly.html' | relative_url }}">
    <div class="emoji">🐼</div>
    <h3>Panda or Grizzly?</h3>
    <p>Upload a photo and find out which bear it looks more like.</p>
  </a>
  <a class="project-card" href="{{ '/project-6-or-7.html' | relative_url }}">
    <div class="emoji">✍️</div>
    <h3>6 or 7?</h3>
    <p>Classify an image of a handwritten digit as a 6 or a 7.</p>
  </a>
</div>
