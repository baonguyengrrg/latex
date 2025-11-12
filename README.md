\documentclass{article}
\usepackage{graphicx} % Required for inserting images

\title{calculus}


\begin{document}

\maketitle
\int_{\frac{\pi}{4}}^{\frac{\pi}{2}}\frac{(x+2\sin(x)-3)\cos(x)}{\sin^3(x){}}dx=\int_{\frac{\pi}{4}}^{\frac{\pi}{2}} \frac{\cos(x)x}{sin^3(x)}dx 
+\int_{\frac{\pi}{4}}^{\frac{\pi}{2}} \frac{2\cos(x)}{sin^2(x)}dx-3\int_{\frac{\pi}{4}}^{\frac{\pi}{2}} \frac{\cos(x)}{sin^3(x)}dx \newline
 \indent \indent \indent \indent \indent \indent \indent\indent \indent  (I)  \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ (II) \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ (III) \newline
(I) \newline
let\ u=x;  \ dv=\frac{\cos(x)}{\sin^3(x)}dx \Rightarrow du=dx;\ v=\frac{-1}{2\sin^2(x)} \newline
\int_{\frac{pi}{4}}^{\frac{\pi}{2}} \frac{\cos(x)x}{\sin^3(x)}dx =\frac{-x}{2\sin^2(x)}  \  \ -\int_{\frac{\pi}{4}}^{\frac{\pi}{2}} \frac{-1}{2\sin^2(x)}dx== 0 - \left( \frac{-1}{2} \cot(x) \right) \bigg|_{\pi/4}^{\pi/2} = \frac{1}{2} \newline \newline
(II) \newline
let  \ a=\sin(x);\ da=\cos(x)dx \newline \newline
(II) = 2\int_{\frac{\sqrt{2}}{2}}^{1} \frac{da}{a^2}=2\sqrt{2}-2 \newline \newline
(III) \newline
let \ b= \sin(x);\ db=\cos(x)dx \newline \newline
(III)=-3\int_{\frac{\sqrt[]{2}}{2}}^{1} \frac{db}{b^3}=\frac{-3}{2} \newline \newline
From \ (I),\ (II),\ and (III) \newline \newline
\int_{\frac{\pi}{4}}^{\frac{\pi}{2}}\frac{(x+2\sin(x)-3)\cos(x)}{\sin^3(x){}}dx=-3+2\sqrt{2}

\end{document}
