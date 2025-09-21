# Research on Remote Control Methods for Quadrotor UAVs Based on IMU

Chinese title: 基于IMU的四旋翼无人机远程遥控方法研究

This repo is the source files of my Master of Engineering Thesis.

## Structure

- `all.tex`: Main file to collect all chapters.
- `config.tex`: Config file.
- `front_pages.tex`: Contain the abstract and the conver.
- `chx.tex`: Every chapter.
- `main.bib`: Citation.

## How to compile

xelatex -> biber -> xelatex*2

``` shell
xelatex -synctex=1 -interaction=nonstopmode -file-line-error %DOCFILE%
biber %DOCFILE%
```
