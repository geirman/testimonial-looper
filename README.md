# Testimonial Looper
Takes a `<span>` element defining an array of testimonials and mimics them being typed out, cycling through them endlessly. Vanilla JS (ES6)


![demo](https://user-images.githubusercontent.com/1640318/53667511-0ca3dc80-3c26-11e9-886c-d7847b4d7915.gif)

## Usage
```
  <span id="testimonials" data-pace="80" data-stall="1500" data-text='[
            "Each team dressed different and made the pictures so fun to look at",
            "Definitely learned the power of teamwork & communication all while having fun!",
            "The challenges were fun, sometimes ridiculous but hilarious at the same time",
            "The kids had so much fun running around and doing silly things"
          ]'></span>
```

* `data-text` (required) An array of testimonials
* `data-pace` (optional) How quickly to render the typed text in milliseconds
* `data-stall` (optional) How long the text should remain typed before deleting


