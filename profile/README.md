![SynaesthetiQ Banner Image](https://github.com/rt5-tp/.github/raw/main/YoutubeBanner.jpg "SynaesthetiQ")

# SynaesthetiQ

SynaesthetiQ is a music visualiser prototype using envelope following, frequency analysis and genre detection to create engaging visualisations of music in real-time. This project was started as part of a Real-time Embedded Programming undergraduate project at the University of Glasgow. These repositories include all of the code written during the project, as the prototype was developed, and for a demonstration.

## One Repo to Rule Them All

The [PuppetMaster](https://github.com/rt5-tp/SynaesthetiQ-PuppetMaster) repository links together other repositories, each containing different submodules of the full SynaesthetiQ processing flow. These submodules are:

* [**Audio Capture**](https://github.com/rt5-tp/SynaesthetiQ-audiocapture) - Handles data acquisition, frequency analysis and a real-time genre classification wrapper.
* [**Envelope Following**](https://github.com/rt5-tp/envelope_following) - A simple envelope follower to visualise  the pulse of music.
* [**LED Library**](https://github.com/rt5-tp/SynaesthetiQ-LED-LIbrary) - Renders visualisations to an array of LEDs.
* [**Genre Classifier**](https://github.com/rt5-tp/cpp_genre_classifier) - Integrates a convolutional neural network for non-real-time genre classification
* [**Genre Prediction Server**](https://github.com/rt5-tp/GenrePredictionServer) - A remote server which uses a neural network to classify the genre of music.

The relationships between these submodules are handled by the [Visualiser](https://github.com/rt5-tp/SynaesthetiQ-PuppetMaster/tree/main/src/Visualiser), which is defined within this repository.

## Go with the Flow

The overall flow of data through these submodules can be represented by this diagram:

<div align="center">
    <img width="100%" src="https://github.com/rt5-tp/.github/blob/main/Full%20Data%20Flow%20Diagram.svg">
</div>

More information on how these submodules work and interact with each other can be found in their respective repositories and the [documentation](https://rt5-tp.github.io/) for this project.

## The Hardest Part

A [hardware](https://github.com/rt5-tp/Synaesthetiq-Hardware-Design) prototype was designed and built to demonstrate the functionality of the SynaesthetiQ software. It centre's around a pair of flexible LED Matrices which have been wrapped around a 3D printed core, placed on top of this core is another larger LED. The big LED is designed to provide a simple envelope following function, where the brightness is proportional to the intensity of sound at that moment, while the matrix should provide a more complex frequency-domain visualisation. This allows for a combination of unique musical visualisation and bright impactful lighting.

## The Friends We Made Along the Way

As the project developed, a number of additional repositories were created to prototype elements of the overall code. They are:

* [**LED Matrix Tests**](https://github.com/rt5-tp/LED_Matrix_Tests) - Code used to test the LED Matrix
* [**Low-res FFT Prototypes**](https://github.com/rt5-tp/low-res_fft_proto) - Prototyping a visualisation
* [**Real-time Spectrogram**](https://github.com/rt5-tp/SynaesthetiQ-SpectrogramClass) - A more complex real-time visualisation method (incomplete)
* [**Spectrogram Non-real-time Prototype**](https://github.com/rt5-tp/SpectroscopeProto) - A prototype real-time spectrogram visualisation method

## The Dream Team

- [**Ross McKeown**](https://github.com/rossamck) 
- [**Thomas Nordentoft**](https://github.com/nordwestt) 
- [**Thomas Burnip**](https://github.com/TBurnip)
- [**Neil Crawshaw**](https://github.com/Neil-A-C)

## Like and Subscribe

[**Youtube**](https://www.youtube.com/@synaesthetiq)

[**TikTok**](https://www.tiktok.com/@synaesthetiq)

[**LinkedIn**](https://www.linkedin.com/company/synaesthetiq/)

[**Instagram**](https://www.instagram.com/synaesthetiq/)
