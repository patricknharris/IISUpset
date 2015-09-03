# UpSet

These files are clone copies of Harvard's UpSet as described below; the javascript files and additional files have been added such that the WebSite will be enabled within IIS and run inside Internet Explorer.
Intent is to branch the UpSet master at some point.

Best Regards
Patrick Harris

## About

UpSet is an interactive, web based visualization technique designed to analyze set-based data. UpSet visualizes both, set intersections and their properties, and the items (elements) in the dataset. Please see the project website at [http://vcg.github.io/upset/about](http://vcg.github.io/upset/about) for details about the technique, publications and videos.

## Demo

We are hosting a demo instance of UpSet at [http://vcg.github.io/upset](http://vcg.github.io/upset).

## Local Deployment

1. Clone the repository using ```git clone``` or download and extract the [ZIP file](https://github.com/VCG/upset/archive/master.zip).
2. Launch the [Python SimpleHTTPServer](https://docs.python.org/2/library/simplehttpserver.html) in the project directory.
 
   ```
   $ python -m SimpleHTTPServer 8000
   ```

3. View UpSet in your browser at [localhost:8000](http://localhost:8000).

Alternatively you can also **run UpSet without a web server**. Chrome does not allow this by default, but Firefox works well. Simply open the index.html file in Firefox. 

## Configuring Datasets

See the project wiki for an [overview of the data definition file format](https://github.com/VCG/upset/wiki/Data-Import) used to describe tabular text files.


