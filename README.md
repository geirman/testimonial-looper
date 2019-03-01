# Testimonial Looper
Takes a `<span>` element defining an array of testimonials and mimics them being typed out, cycling through them endlessly. Vanilla JS (ES6)

## Usage
```
  <span id="testimonials" data-pace="80" data-stall="1500" data-text='[
            "Each team dressed different and made the pictures so fun to look at",
            "Definitely learned the power of teamwork & communication all while having fun!",
            "The challenges were fun, sometimes ridiculous but hilarious at the same time",
            "The kids had so much fun running around and doing silly things"
          ]'></span>
```

| Attribute     | Description           |
| ------------- |:-------------:| -----:|
| `data-pace`     | How quickly to render the typed text in milliseconds |
| `data-stall`      | How long the text should remain typed before deleting      |
| `data-text` | An array of testimonials      |