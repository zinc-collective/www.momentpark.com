# www.momentpark.com

MomentPark is a series of affordable, accessible, and easy to use photography and videography apps where every shot is unique.

These apps are also 100% source available. We intend to license them under an OSI or FSF approved license, [once there is one that gives us the right to restrict licenses to actors who violate human rights.](https://ethicalsource.dev).

They are currently freely available for personal use; with a compiled and signed version available for purchase on the App Store.

## Applications

- **HomeMovies** - ([buy](https://apps.apple.com/us/app/home-movies-video/id1075104413), [compile and run](https://github.com/zinc-collective/mp-home-movies)) - Remember when taking home movies was as easy as "Press-to-record.  Release-to-Pause. Press-again-to-resume-recording?" Well you're in luck, we did too! And when the original developers were looking for someone to steward the app into the public domain, we jumped at the chance. The design and the code could use some thoughtful love and affection; but we have gotten it to the point where it can be compiled and installed.
- **PlasticBullet** - ([buy](https://apps.apple.com/us/app/plastic-bullet/id372405516), [compile and run](https://github.com/zinc-collective/mp-plasticbullet)) - Plastic Bullet procedurally generates artistically tuned, unique filters. Never see the same combination of vignettes, light bleed, or grain again. Don't like what you see? Get a new set of options with the touch of a button. No more tweaking, tuning or futzing about; photo in, art out. Currently, this is both compiling _and_ getting a facelift to make it work better on modern phones.
- **MovieLooks** - ([buy](https://apps.apple.com/us/app/movie-looks/id409948907), [compile and run](https://github.com/zinc-collective/mp-movielooks)) - Emotional impact and fantastic color treatment, all in a clean and simple editor that lets you focus on your best shots. Sadly, the underlying videography engine needs an update to play well with 4k; and it does not compile in modern xCode. If you can help, we'd appreciate it.

- **CrossProcess** - ([buy](https://apps.apple.com/us/app/cross-process/id355754066), [compile and run](https://github.com/zinc-collective/mp-crossprocess)) - Cross-processing is one of the most fun and accessible techniques for film photography afficianados. Now you can do it right from your phone, with a high degree of algorithmic realism. CrossProcess mostly works on existing phones, but does not yet compile particularly easily and has some rendering artifacts on iPhones with a notch. Help wanted!

- **NoirPhoto** - ([buy](https://apps.apple.com/us/app/noir-photo/id429484353), [compile and run](https://github.com/zinc-collective/mp-noirphoto)) - If you want that 20s look; you've come to the right place. Dramatic lighting, focal points, and contrast all come together in a tight and intuitive user interface. CrossProcess mostly works on existing phones, but does not yet compile particularly easily and has some rendering artifacts on iPhones with a notch. Help wanted!

## Development Setup

This site is build using [Eleventy](http://11ty.dev/).

### Prerequisite:

Please install node & npm.

[Node Version Manager](https://github.com/nvm-sh/nvm) is recommended for easy NodeJS version management.

Run the following command to start developing.
```
# Install all node dependencies
npm i
# Start development server
npm start
```
