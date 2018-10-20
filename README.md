# Introduction-to-Probability

Grinstead and Snell’s Introduction to Probability from https://math.dartmouth.edu/~prob/prob/

## Notes on build

Run `make -c prob`. Original script `zzz` is included as well.

TexLive regular or full installation would be good.

If [TinyTex](https://yihui.name/tinytex/) is preferred, however, some of the missing packages won't be detected by `tinytex::lualatex("prob.tex")`

Install some important ones with `tinytex::tlmgr_install(c("adobemapping","epstopdf","fandol"))`
