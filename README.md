<h2>Mathly Turns Lua into a Tiny, Free but Powerful MATLAB</h2>

<p>Mathly for <a href=https://www.lua.org>Lua</a> is a Lua module which turns Lua into a tiny, free but powerful MATLAB. It provides a group of commonly
used MATLAB functions and features, for example,  <em>linspace</em>, <em>zeros</em>, <em>rand</em>, <em>save</em>, <em>plot</em>, <em>plot3d</em>, and
convenient matrix operations as well. If there are things many love the most about MATLAB, these tools are. They make coding and testing a thought much
easier and faster than working in most other programming languages.</p>

<p>Mathly uses <a href=https://plotly.com/javascript/>Plotly JavaScript</a> graphing tools to plot graphs. Therefore, graphs are
shown in an internet browser.</p>

<p>The entire mathly tool together with Lua interpreter is less than 5 MB, while providing enough features for instructors and college students
to implement numerical algorithms. Because it is super lightweight and fast as well, it can run fast even on old and slow devices like 
Microsoft Surface Pro 4 (Intel Core i5-6300U with 8 GB RAM). In contrast to it, MATLAB needs a few GB of storage space. In addition, 
it takes about 22 seconds to start MATLAB R2024b on a brand new high-end Intel Core i9-14900HX laptop with 56 GB RAM. Thus, it can hardly 
be installed on slow or pretty old computers and run smoothly.</p>

<p>Mathly is especially a good choice for instructors of linear algebra and numerical computing for teaching. It takes no time to
start Lua with mathly loaded. While developing code and doing computation in a lecture, they can simply focus on delivery
of course contents and never need to worry if their computers work too slowly. Moreover, Lua is so
simple and so natural a language that students without programming skills can understand most of Lua code.</p>

<p>&#x2713; &nbsp; Please access <a href=https://github.com/fdformula/MathlyLua>mathly</a> for more information.</p>

<h2>Finite Difference Formula Toolkit</h2>

<p>The Julia package, also ported to Python, provides a general and comprehensive toolkit
for generating finite difference formulas, working with Taylor series expansions, and teaching/learning finite difference formulas. It generates
finite difference formulas for derivatives of various orders by using Taylor series expansions of a function at evenly spaced points. It also gives
the truncation error of a formula in the big-O notation. We can use it to generate new formulas in addition to verification of known ones. By
changing decimal places, we can also investigate how rounding errors may affect a result.</p>

<p>Beware, though formulas are mathematically correct, they may not be numerically useful. This is true especially when we derive formulas for a
derivative of higher order. For example, run <em>compute(9, -5:5)</em>, provided by this package, to generate a 10-point central formula for the 9-th
derivative. The formula is mathematically correct, but it can hardly be put into use for numerical computing without, if possible, rewriting it
in a special way. Similarly, the more points are used, the more precise a formula is mathematically. However, due to rounding errors, this may
not be true numerically.</p>

<p>&#x2713; &nbsp; Please access the toolkit in <a href=https://github.com/fdformula/FiniteDifferenceFormula.jl>Julia</a> or
<a href=https://github.com/fdformula/FiniteDifferenceFormula.py>Python</a> for more information.</p>

</body>
</html>
