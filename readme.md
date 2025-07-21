# DBiswas-CV

A simple template for academic CVs in a single column format using LuaLaTeX. It is geared towards students pursuing higher education (MSc, PhD etc.), especailly in the basic sciences.

## Details

The folder structure of the repository is as follows:

```
|---readme.md: Details about the template and basic usage information.
|---main.tex: The main file with basic information.
+---info
    |---conf_workshops-talks.tex: Contains information about conferences, workshops attended.
    |---education.tex: Contains information about formal education and degrees earned.
    |---experience.tex: Contains information about work experience and/or internships.
    |---skills.tex: Contains information about the acquired skills.
    |---misc.tex: Contains miscellanous information.
    |---mypapers.bib: Contains the bibentries for papers published.
+---extras
    |---sign.png: Signature of the candidate.
    |---references.tex: Contains information about the references of the candiate.
```

The basic file which needs to be updated and compiled is _main.tex_. All the necessary information is to be put in the corresponding .tex files in the _info_ folder. 

In certain cases, recruiters and HRs ask for a signed CV and/or a list of references to be included. Those are placed in the _extras_ folder. To use those features, un-comment the relevant sections towards the end in _main.tex_ and update the files in _extras_ accordingly.

## Contact

Dhrubajyoti Biswas, _Email: dhrubajyoti98@gmail.com_, _Web: dhrubajyoti98.github.io_.