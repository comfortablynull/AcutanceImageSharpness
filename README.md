AcutanceImageSharpness
======================

Image Sharpness By Method of Acutance
By Lam Tran


http://en.wikipedia.org/wiki/Acutance



Description:
Image sharpness is a difficult measure. Typical methods use Fourier Analysis, 
applying some sort of convolution sometimes and then doing statistics. 

I found using Acutance to provide some decent broad benchmarks on how sharp an image is. It comes in handy when your comparing images with completely different content

It is also far easier algorithmically, providing some sort of performance gain 
(however using php kind of erases that)


HOW TO USE:

$class = new Acutance($file_location);
$result = $class->process();


TODO:

Examples<br>
Input as URL instead of local file<br>
Exception Catching<br>
Composer Package?<br>

