# `hiRes` - the repo that will improve the resolution of my old images

### Chris Hamm
### 2023-08-30


**To cut a segment out of an .`mp4`:**
ffmpeg -i Monsanto_Night.mp4 -ss 30 -t 60 -c:a copy Monsanto_trimmed.mp4


# Major commits
1. 2023-08-30: Initial commit with working tool for images and first take on a video upscaler
1. 2023-08-31: The video upscaler needs a lot of work. Oversampled the Monsanto Night video. This looks bad even at x2.
1. 2023-09-15: Updated to run on my new 4070. Now finishes How's image.
