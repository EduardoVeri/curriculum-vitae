# curriculum-vitae

## Requirements 

My CV was made by using [rendercv](http://github.com/rendercv/rendercv): a command-line open-source tool to render CVs from YAML data.

To use it:
- Install Python 3.10 or higher
- Install rendercv by running `pip install rendercv`
- Create a YAML file with the data of your CV. There's examples of yaml files in the oficial repository of rendercv.
- Run `rendercv render your_cv.yaml -o your_cv_folder` to render it

## Compile CVs

### My CV
```bash
rendercv render Eduardo_CV.yaml -o Eduardo_CV
```

### My Girlfriend's CV
```bash
rendercv render Julia_CV.yaml -o Julia_CV
```