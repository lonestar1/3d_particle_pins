# Project Title

For a Sony Robots TVC there was a concept needed that would transition a robot into a human when he heard music. This was the foundation of that development. The pins wave is driven by music with a layer of noise added on top to keep it organic. 

## Getting Started

Open the completed Maya scene to observe the particle animation. The sound track has already been extracted and baked in here. 

### Prerequisites

Autodesk Maya
Windows 32 bit OS to run the wav to asci software. This is DOS software.

## Running the tests

1) Select a wav file (or snippet) and convert it to mono 8 bit using your favourite audio software. Adobe Audition or similar.
2) Convert the wav to an asci file using the wav to asci software.*
3) Clear the animation from the Y attribute on locator1 in the Maya scene.
4) Copy and paste the Mel script into your Maya script editor, set the path to the asci file and run.

NB. This is 32 bit software and runs in DOS. There is source code there so with a little bit of effort this could be recompiled.

## Built With

Autodesk Maya

## Authors

* **Andreas Wanda** - *Initial work* - [lonestar1](https://github.com/lonestar1)
[www.andreaswanda.com](http://www.andreaswanda.com)

Thanks to Tjalling Nijboer for writing the wav to asci convertor (whoever you are!)

## License

This project is licensed under the GNU License - see the [LICENSE](LICENSE) file for details

## Acknowledgments

* Also thanks to FUEL International Sydney (post production house that no longer exists unfortunately)
* And thanks to Ben Harper for his snippet of Faded
