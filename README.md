# Ticapsoriginal Site Wide Reading Time
Ticapsoriginal calculates total time to read an entire site based on all sitemaps urls

* large sitemaps available
* detect paragraphs, titles and strong texts 

# make python environment:
* Install pip first:
<pre><code>sudo apt-get install python3-pip
</code></pre>
* Then install virtualenv using pip3
<pre><code>sudo pip3 install virtualenv 
</code></pre>
* Now create a virtual environment
<pre><code>virtualenv venv
</code></pre>
* Active your virtual environment:
<pre><code>source venv/bin/activate
</code></pre>
* Enter on environment:
<pre><code>cd venv
</code></pre>

## Install tqdm to see progress bar: 
<pre><code>pip install tqdm
</code></pre>

## Install resquests to get responses: 
<pre><code>pip install requests
</code></pre>

## Install beautifull soap to read web content data: 
<pre><code>pip install bs4
</code></pre>

## Install advertools to read large url data: 
<pre><code>pip install advertools
</code></pre>

## Clone Ticapsoriginal Site Wide Reading Time repository:
<pre><code> git clone https://github.com/Tinoco/Ticapsoriginal_site_wide_reading_time.git
</code></pre>

* Change the allreadtime.py file with your sitemap url 

## Start scanning and calculating:
<pre><code>python allreadtime.py
</code></pre>

![](https://ticapsoriginal.com/static/allreadtime.png)

## quality:
* [`100% pycodestyle coverage`](https://pypi.org/project/pycodestyle/)

* [`0% code plagiarism detected`](https://github.com/blingenf/copydetect)



