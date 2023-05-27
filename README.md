# Simple Waveform Progressbar

A simple progressbar made using wave-like bars.



## Usage

```dart
SizedBox(
              width: double.infinity,
              height: 20,
              child: Center(
                child: WaveformProgressbar(
                  color: Colors.grey,
                  progressColor: Colors.red,
                  progress: progress,
                  onTap: (progress) {
                    var tt = progress;
                  },
                ),
              ),
            ),
```
<img src="https://i.ibb.co/SthjfVR/Isolated.png"
alt="progressbar"
style="float: left; margin-right: 10px;" />
## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)