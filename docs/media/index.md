# Video Library

A curated set of embedded clips, trailers, and interviews. Everything here is a public YouTube upload, embedded rather than rehosted; nothing is mirrored or redistributed by this project.

<div class="grid cards" markdown>

-   :material-movie-play: **[Scenes & Trailers](scenes.md)**

    ---

    The baptism, the offer, the trailers, and the moments the films are argued about.

-   :material-microphone: **[Interviews](interviews.md)**

    ---

    Coppola, Pacino, Caan, Duvall, Brando, and the Oscar refusal — in their own words.

-   :material-camera-iris: **[Craft & Video Essays](craft.md)**

    ---

    Gordon Willis on lighting, and the best analytical breakdowns of the photography.

</div>

---

## How embeds work here

Videos are embedded through **youtube-nocookie.com**, which suppresses the tracking cookies a standard YouTube embed sets before you press play. They load lazily, so pages with several clips still open quickly.

!!! warning "Links rot"
    This is the most fragile part of the wiki. YouTube uploads get taken down, made private, or region-locked without notice, and clips from a Paramount film are more prone to it than most. Every video here was verified when added; some will inevitably break.

    **Found a dead embed?** [Open an issue](https://github.com/joedef/godfather-wiki/issues) or replace it in a pull request. Preference order for replacements: an official **Paramount** channel upload, then a documented archival or press channel, then anything else.

## What we don't embed

- Full films or substantial portions of them
- Re-uploads that strip the original uploader's credit
- Anything behind a paywall that the embed can't actually play

## Adding a video

Use this pattern — plain HTML, no libraries:

```html
<div class="video">
  <iframe src="https://www.youtube-nocookie.com/embed/VIDEO_ID"
          title="Short description"
          loading="lazy" allowfullscreen
          allow="accelerometer; clipboard-write; encrypted-media; picture-in-picture; web-share"
          referrerpolicy="strict-origin-when-cross-origin"></iframe>
</div>
<p class="video-caption"><strong>Title.</strong> One or two sentences on what it is and why
it's worth watching. — <em>Channel name</em></p>
```

Write the caption so the entry still means something after the video dies. A caption that just says "watch this" is worthless the moment the embed goes dark; one that says what the clip contains still tells a reader what to go and look for.
