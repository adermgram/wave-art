# wave Art

`wave art` is a simple Go program that generates animated Lissajous curves and outputs them as GIFs. It demonstrates harmonic motion using sine waves and creates a looping animation of the resulting patterns.

## ✨ Features
- Generates animated Lissajous figures.
- Outputs directly to standard output as a GIF (can be redirected to a file).
- Uses only Go's standard library.
- Randomized frequency for unique results on each run.

## 🖼️ Output Example
![out](https://github.com/user-attachments/assets/816ea131-66a8-4aca-a28f-1baa3d179f5b)

Run the program and redirect the output to a `.gif` file:

```bash
go run wave_art.go > output.gif
