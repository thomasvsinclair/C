Using Latex to create my personal resume. 

### Inspiration
Based on 
 [sb2nov/resume](https://github.com/sb2nov/resume)
and 
 [jakegut/resume](https://github.com/jakegut/resume.git).

### Build using Docker
using windows cmd
```sh
docker build -t mi-latex-image 
set currentDir=%cd%
docker run --rm -v %currentDir%:/data -w /data mi-latex-image pdflatex nicolas_cejas_resume.tex
```

### Preview

![Resume Screenshot](/resume_preview.png)


