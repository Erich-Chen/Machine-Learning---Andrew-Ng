# Machine-Learning---Andrew-Ng

I have enrolled the course `Machine Learning` tought by professor Andrew Ng on couresa since July 9th, 2018. 

https://www.coursera.org/learn/machine-learning/

I found it very helpful to read supplement pages after each video. 
I copied out them and formate with markdown plus MathJax enhancement. Such that I can leave my own notes easily. 

This public repo only stores orignal contents. My private notes are excluded by a .gitignore file. So please feel free to fork your own copy if you like :-) 


## My solution to render Math Equations on github repo

I installed chrome extension `Markdown Viewer` 

- Chrome WebStore: 
    https://chrome.google.com/webstore/detail/markdown-viewer/ckkdlimhmcjmikdlpkmbgfkaikojcbjk

- github: 
    https://github.com/simov/markdown-viewer

Set up `Markdown Viewer`: 

1. Click on the Markdown Viewer icon then 'CONTENT' tab and tick "autoreload", "mathjax"(must), "scroll" and "toc". 

2. Click on the Markdown Viewer icon and select 'Advanced Options'. Then ADD "raw.githubusercontent.com" into `Allowed Origins`. 

**NOTE:** Do not add "github.com"! 

3. Tick CSP (Disable Content Security Policy) under origin "HTTPS://raw.githubusercontent.com". 

4. Click "RAW" button in a github repo, the markdown pages will be rendered by Markdown Viewer instead of raw plaintext. 

## Test Equations: 

Below math equations will correctly displayed when you click 'RAW' button for this file. 

- $E = mc^2$

- \( A_i = B_i + C_i \sum_{k=0}^{i} D_k E^k \)

- \begin{eqnarray}
  A_i &=& B_i + C_i \sum_{k=0}^{i} D_k E^k \\
  F_i &=& \int_{-\infty}^{x_i} f(x) dx
\end{eqnarray}

- $\frac{w_x}{\sum_z x_z}$
- $\frac{w}{\sum_{z} x_z}$
- $x_\gamma = x_i$
- $x_i = x_\gamma$

Cost function of logistic regression (revision):

$$J(\theta) = - \frac{1}{m} \sum_{i=1}^m [ y^{(i)}\ \log (h_\theta (x^{(i)})) + (1 - y^{(i)})\ \log (1 - h_\theta(x^{(i)}))] + \frac{\lambda}{2m}\sum_{j=1}^n \theta_j^2$$

For Neural Networks, it is:

$$
J(\Theta) = - \frac{1}{m} \sum_{i=1}^m \sum_{k=1}^K \left[y^{(i)}_k \log ((h_\Theta (x^{(i)}))_k) + (1 - y^{(i)}_k)\log (1 - (h_\Theta(x^{(i)}))_k)\right] + \frac{\lambda}{2m}\sum_{l=1}^{L-1} \sum_{p=1}^{s_l} \sum_{n=1}^{s_{l+1}} ( \Theta_{n,p}^{(l)})^2
$$
