# Resume Generator

> Focus on the data, not the style!

## Instructions

- First clone the repository by running:
  > `git clone https://github.com/ayan-b/resume-generator`
  or you can also download:  
  ![screenshot](./screenshot.png)
- Then, install all the necessary dependencies from `requirements.txt`:
  > pip install -r requirements.txt
- Check the data file at `config/data.yml`. Change it according to your profile.
- Now run `moban` in your terminal to make the tex file of yout resume!<sup>[1](#moban_footnote)</sup>
- At last, use your favorite LaTeX editor to generate the PDF file! Alternatively,
you can also use some online compiler like [Overleaf](https://www.overleaf.com?r=8bd8a7a4&rm=d&rs=b)<sup>[2](#overleaf)</sup>.

You can also use travis for generating the PDF. Simply follow the `.travis.yml` of this repo.
You can check the rendered pdf files inside the `resume/pdf` folder.

## TODO

Support more templates:
- Awesome-CV: https://github.com/posquit0/Awesome-CV
- Deedy-Resume: https://github.com/deedy/Deedy-Resume

## Credits

The resume templates are taken from the following repositories. The original tex
files can be found inside the `assets` folder.
- sb2nov-resume: https://github.com/sb2nov/resume, _MIT License_

## Contributing

Want to contribute? Awesome! :tada: You can contribute by:
- Adding more templates (that would be super sweet of you!)
- Submitting bugs that you have encountered
- Submitting pull requests for the existing issues

---

<a name="moban_footnote">1</a>: The project uses `moban`. `moban` offers a wide variety of configurations.
Find more at https://moban.readthedocs.io.

<a name="overleaf">2</a>: This is a referral link. I may receive some benefits if you sign up through this
link.
