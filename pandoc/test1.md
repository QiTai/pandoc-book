### Command for Chinese Font !

+ pandoc Placement.md -s -o Placement.pdf --latex-engine=xelatex -V mainfont="SimSun"
+ pandoc Placement.md -s -o Placement.pdf --latex-engine=xelatex --template=pm-template
+ pandoc Placement.md -s -o Placement.pdf --latex-engine=xelatex --template=pm-template --toc

### command to produce PDF slide using beamer

+ pandoc -t beamer slides.md -V theme:Warsaw -o slides.pdf

+ pandoc -t beamer slides.md -V theme:Madrid -o slides.pdf

### Test for CPP code !

```cpp
	for (int i = 0; i < N; i++) {
		int j = i + 1;
	}
```

### Test for Math Formula !
Inline math equations go in like so: $\omega = d\phi / dt$. Display
math should get its own line and be put in in double-dollarsigns:

$$I = \int \rho R^{2} dV$$