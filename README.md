# Active Noise Cancel

A small browser microphone-processing demo.

## Echo/feedback prevention

The page requests the browser's built-in echo cancellation, noise suppression, and automatic gain control. It deliberately does **not** route live microphone audio to the speakers, which prevents the app from feeding speaker output back into the microphone.

This is not full active noise cancellation (ANC). Browser-based phase inversion played through speakers is not reliable ANC because of room acoustics and processing latency, and it can cause loud feedback. Real ANC generally needs calibrated microphones and speakers/headphones with very low-latency processing.

## Run

Open the page on GitHub Pages or another HTTPS origin, then allow microphone access when prompted. Microphone access generally requires HTTPS or localhost.
