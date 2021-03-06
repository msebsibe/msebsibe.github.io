
<body class="jp-Notebook" data-jp-theme-light="true" data-jp-theme-name="JupyterLab Light">

<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>Examining the Hidden Gems: Wine for Casuals Consumer</p>

</div>
</div>
</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>Matthew Sebsibe</p>

</div>
</div>
</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><strong>Introduction</strong></p>

</div>
</div>
</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>While researching topics to focus on I went to Total Wine to buy my sister a gift. There I felt overwhelmed by the analysis paralysis that is a Walmart for wine. Displayed in the chart below are some classifications of wine. It is very expanisve. There are over 10,000 wine grape varieties in the world. Some major categories include: red, white, rose, sparkling and fortified wine. Personally, I wanted to create a project that I felt would be useful to myself in understanding this massive space. In addition, my goal is to use Data Science to simplify the area. Wine is synonymous to snobbery, however, there are many great bottles for relatively cheap. I will also explore if higher priced wine is worth it, but that will be explained more in subsequent sections.</p>

</div>
</div>
</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><img src="https://thewinewankers.files.wordpress.com/2014/02/a-different-types-of-wine-infographic-chart3.png" width=1000 height=500 /></p>

</div>
</div>
</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>Helpful resources: 
The image found above is from the book Wine Folly. I highly reccomend this for beginners intimdated by all the complexities of wine. This book is a good first step in understanding some terms Sommeliers use and different components that distinguish varieties of wine. As an added bonus, the book provides a lot of wine/food pairings. This book is good to get at libraries for its outstanding visuals.</p>

</div>
</div>
</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>Youtube Channels:
<a href="https://www.youtube.com/user/askawinemaker/videos">https://www.youtube.com/user/askawinemaker/videos</a>
<a href="https://www.youtube.com/user/WineAlign">https://www.youtube.com/user/WineAlign</a></p>
<p>I learn best through visual and audio means so seeing someone explain features of bottles as well as basic wine ettiquette has helped me and I believe can be useful to others.</p>

</div>
</div>
</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>For the analysis of our data we will follow the The Data Science Pipeline in order to understand more about the data in front of us</p>

</div>
</div>
</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><strong>Disclaimer: This project is meant to explore the topic of wine in a healthy manner. Please practice safe and lawful consumption of alcohol. Be safe and know your limits.</strong></p>

</div>
</div>
</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><strong>Data Collection/Curation</strong></p>

</div>
</div>
</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">

</div>
</div>
</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>For my dataset, I was lucky to find one on Kaggle with over 100,000 entries. The link can be found here: <a href="https://www.kaggle.com/datasets/christopheiv/winemagdata130k">https://www.kaggle.com/datasets/christopheiv/winemagdata130k</a> . I was able to download this data in a CSV (Comma-separated values) file. What this means is a text-file that is seperated by commas to distinguish information. Within this dataset are many useful columns including the name of the bottle, country of origin, price, description, and points. Points refer to a score out of 100 that refer to the level of wine a sommelier would rate a wine. Wine Spectator a renowned wine magazine with 400000+ wine expert wine ratings has blind-taste tests of wine and scores wine using this scale:</p>
<p>95-100 Classic: a great wine</p>
<p>90-94 Outstanding: a wine of superior character and style</p>
<p>85-89 Very good: a wine with special qualities</p>
<p>80-84 Good: a solid, well-made wine</p>
<p>75-79 Mediocre: a drinkable wine that may have minor flaws</p>
<p>50-74 Not recommended</p>
<p>Different websites and magazines approach the scale differently, but the general trend is similar with preferences given to bottles over 90+ being excellent bottles. Without this dataset, the way I would approach scrapping is by doing a quick google search of wine data. Vivino is a great example of a website that stores many different reviewes of wine. However, it is very expansive and sorts by type of wine. So I would scrape a few thousand from each variety with a goal of about 10000+ reviews to have a good representation of bottom,mid, and high shelf wine from a multitude of wine varieties. Similar to Project 1, the data is tabulated fairly easily to scrape the HTML with BeautifulSoup. Luckly the dataset I found from Kaggle did a similar approach using data from WineMag. For the purposes of this project, the scale described above matches, but for Wine Magazine specific scale, that can be found in the link here: <a href="https://www.winemag.com/2010/04/09/you-asked-how-is-a-wines-score-determined/">https://www.winemag.com/2010/04/09/you-asked-how-is-a-wines-score-determined/</a> . Wine Enthusiast Magazine also referred to as Wine Mag has some great resources for finding bottles of wine for every budget and is a great resource for beginners and experts alike to learn something new.</p>

</div>
</div>
</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><strong>Data Management / Representation</strong></p>

</div>
</div>
</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>For this project we will rely heavily on the Pandas library to represent our data. The matplot and seaborn library will be key in visualizing our data. Finally numpy will be key in preforming various operations on our data. As described above, the data is stored in a csv file. Once the file is imported into the Jupyter Notebook, all that is needed is to call the read_csv file to import all of the data stored. From there, it is the job of the data scientist to massage the data and make choices about missing data. For this data set, I can immediately drop the taster name, twitter handle, and unnamed column as none of these columns store useful data for our analysis.</p>

</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[1]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">import</span> <span class="nn">pandas</span> <span class="k">as</span> <span class="nn">pd</span>
<span class="kn">import</span> <span class="nn">matplotlib.pyplot</span> <span class="k">as</span> <span class="nn">plt</span>
<span class="kn">import</span> <span class="nn">seaborn</span> <span class="k">as</span> <span class="nn">sns</span>
<span class="kn">import</span> <span class="nn">numpy</span> <span class="k">as</span> <span class="nn">np</span>
<span class="kn">from</span> <span class="nn">scipy</span> <span class="kn">import</span> <span class="n">stats</span>
</pre></div>

     </div>
</div>
</div>
</div>

</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>Lets take a peek into our data.</p>

</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[2]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#wine set before dropping unnecessary operations</span>
<span class="n">wine_data</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s2">&quot;winemag-data-130k-v2.csv&quot;</span><span class="p">)</span>

<span class="c1">#Taster name and twitter tag are unnecesary for analysis</span>
<span class="n">wine_data</span><span class="o">.</span><span class="n">drop</span><span class="p">(</span><span class="s2">&quot;taster_name&quot;</span><span class="p">,</span> <span class="n">axis</span><span class="o">=</span><span class="mi">1</span><span class="p">,</span> <span class="n">inplace</span><span class="o">=</span><span class="kc">True</span><span class="p">)</span>
<span class="n">wine_data</span><span class="o">.</span><span class="n">drop</span><span class="p">(</span><span class="s2">&quot;taster_twitter_handle&quot;</span><span class="p">,</span> <span class="n">axis</span><span class="o">=</span><span class="mi">1</span><span class="p">,</span> <span class="n">inplace</span><span class="o">=</span><span class="kc">True</span><span class="p">)</span>
<span class="n">wine_data</span><span class="o">.</span><span class="n">drop</span><span class="p">(</span><span class="s2">&quot;Unnamed: 0&quot;</span><span class="p">,</span> <span class="n">axis</span><span class="o">=</span><span class="mi">1</span><span class="p">,</span> <span class="n">inplace</span><span class="o">=</span><span class="kc">True</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>For the dataset we have many different characteristics described in the kaggle spec:</p>
<p>country-The country that the wine originates from</p>
<p>description- An added description of some bottles in the dataset</p>
<p>designation-The vineyard within the winery where the grapes that made the wine are from</p>
<p>points-The point value that WineEnthusiast rated the wine on a scale of 1-100</p>
<p>price-The cost for a bottle of the wine</p>
<p>province-The province or state that the wine is from</p>
<p>region_1:The wine growing area in a province or state (ie Napa)</p>
<p>region_2:Sometimes there are more specific regions specified within a wine growing area (ie Rutherford inside the Napa Valley),</p>

</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[3]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">wine_data</span><span class="o">.</span><span class="n">info</span><span class="p">()</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>


<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="text/plain">
<pre>&lt;class &#39;pandas.core.frame.DataFrame&#39;&gt;
RangeIndex: 129971 entries, 0 to 129970
Data columns (total 11 columns):
 #   Column       Non-Null Count   Dtype  
---  ------       --------------   -----  
 0   country      129908 non-null  object 
 1   description  129971 non-null  object 
 2   designation  92506 non-null   object 
 3   points       129971 non-null  int64  
 4   price        120975 non-null  float64
 5   province     129908 non-null  object 
 6   region_1     108724 non-null  object 
 7   region_2     50511 non-null   object 
 8   title        129971 non-null  object 
 9   variety      129970 non-null  object 
 10  winery       129971 non-null  object 
dtypes: float64(1), int64(1), object(9)
memory usage: 10.9+ MB
</pre>
</div>
</div>

</div>

</div>

</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>For this model, I have chosen to drop rows without a wine bottle name, price, and point value. These will be needed in later sections and since we have so many data points we will still have many values to work with as shown below.</p>

</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[4]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#Dropping columns that do not have a price, point, or wine bottle name</span>
<span class="n">before</span> <span class="o">=</span> <span class="nb">len</span><span class="p">(</span><span class="n">wine_data</span><span class="o">.</span><span class="n">index</span><span class="p">)</span>

<span class="n">wine_data</span> <span class="o">=</span> <span class="n">wine_data</span><span class="o">.</span><span class="n">dropna</span><span class="p">(</span><span class="n">subset</span><span class="o">=</span><span class="p">[</span><span class="s1">&#39;price&#39;</span><span class="p">,</span><span class="s1">&#39;points&#39;</span><span class="p">,</span><span class="s1">&#39;title&#39;</span><span class="p">])</span>

<span class="n">after</span> <span class="o">=</span> <span class="nb">len</span><span class="p">(</span><span class="n">wine_data</span><span class="o">.</span><span class="n">index</span><span class="p">)</span>

<span class="n">tot</span> <span class="o">=</span> <span class="n">before</span> <span class="o">-</span> <span class="n">after</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Number of values dropped = &quot;</span> <span class="o">+</span> <span class="nb">str</span><span class="p">(</span><span class="n">tot</span><span class="p">))</span>

<span class="n">tot</span> <span class="o">=</span> <span class="n">tot</span><span class="o">/</span><span class="n">before</span>
<span class="n">tot</span> <span class="o">=</span> <span class="n">tot</span><span class="o">*</span><span class="mi">100</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Percent of values dropped = &quot;</span> <span class="o">+</span> <span class="nb">str</span><span class="p">(</span><span class="n">tot</span><span class="p">)</span> <span class="o">+</span> <span class="s2">&quot;%&quot;</span><span class="p">)</span>

<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Number of values left = &quot;</span> <span class="o">+</span> <span class="nb">str</span><span class="p">(</span><span class="n">after</span><span class="p">))</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>


<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="text/plain">
<pre>Number of values dropped = 8996
Percent of values dropped = 6.921544036746659%
Number of values left = 120975
</pre>
</div>
</div>

</div>

</div>

</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><strong>Since we still have over 120000 values to work with we can move forward with this model.</strong></p>

</div>
</div>
</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>In our model I utilized a CSV with data already in it. However, if we want to scrape data ourselves, we can take an approach similar to Project 1.</p>

</div>
</div>
</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>The approach I would take would be to find a website that has data formatted similar to the HTML table. There are many great websites to pick from like Vivino and WineMag. From there we can use, beautiful soup to help "prettify" our data and have it formatted to our liking. From there we call the pandas read_csv function in order to have that formatted into a data set similar to how we have our dataframe above. The import requests library I imported above is utilized to allow our data to get it using the requests library.</p>

</div>
</div>
</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>Explanatory Data Analysis</p>

</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[5]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Analyze Stats for Price</span>
<span class="n">mean</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">mean</span><span class="p">(</span><span class="n">wine_data</span><span class="p">[</span><span class="s1">&#39;price&#39;</span><span class="p">])</span>
<span class="n">median</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">median</span><span class="p">(</span><span class="n">wine_data</span><span class="p">[</span><span class="s1">&#39;price&#39;</span><span class="p">])</span>
<span class="n">mini</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">min</span><span class="p">(</span><span class="n">wine_data</span><span class="p">[</span><span class="s1">&#39;price&#39;</span><span class="p">])</span>
<span class="n">maxi</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">max</span><span class="p">(</span><span class="n">wine_data</span><span class="p">[</span><span class="s1">&#39;price&#39;</span><span class="p">])</span>
<span class="n">stddev</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">std</span><span class="p">(</span><span class="n">wine_data</span><span class="p">[</span><span class="s1">&#39;price&#39;</span><span class="p">])</span>

<span class="nb">print</span><span class="p">(</span><span class="s1">&#39;SUMMARY STATS FOR PRICE OF WINE IN THE DATASET&#39;</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="s1">&#39;Mean: &#39;</span><span class="p">,</span> <span class="n">mean</span><span class="p">,</span> <span class="s1">&#39;</span><span class="se">\n</span><span class="s1">Std Dev: &#39;</span><span class="p">,</span> <span class="n">stddev</span><span class="p">,</span> <span class="s1">&#39;</span><span class="se">\n</span><span class="s1">Median: &#39;</span><span class="p">,</span> <span class="n">median</span><span class="p">,</span> <span class="s1">&#39;</span><span class="se">\n</span><span class="s1">Min: &#39;</span><span class="p">,</span> <span class="n">mini</span><span class="p">,</span> <span class="s1">&#39;</span><span class="se">\n</span><span class="s1">Max: &#39;</span><span class="p">,</span> <span class="n">maxi</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>


<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="text/plain">
<pre>SUMMARY STATS FOR PRICE OF WINE IN THE DATASET
Mean:  35.363389129985535 
Std Dev:  41.022048119411714 
Median:  25.0 
Min:  4.0 
Max:  3300.0
</pre>
</div>
</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[6]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">plt</span><span class="o">.</span><span class="n">figure</span><span class="p">(</span><span class="n">figsize</span><span class="o">=</span><span class="p">(</span><span class="mi">20</span><span class="p">,</span><span class="mi">15</span><span class="p">))</span>
<span class="n">ax</span> <span class="o">=</span> <span class="n">sns</span><span class="o">.</span><span class="n">countplot</span><span class="p">(</span><span class="n">x</span><span class="o">=</span><span class="s2">&quot;country&quot;</span><span class="p">,</span> <span class="n">data</span><span class="o">=</span><span class="n">wine_data</span><span class="p">)</span>
<span class="n">ax</span><span class="o">.</span><span class="n">set_xticklabels</span><span class="p">(</span><span class="n">ax</span><span class="o">.</span><span class="n">get_xticklabels</span><span class="p">(),</span><span class="n">rotation</span> <span class="o">=</span> <span class="mi">75</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedImage jp-OutputArea-output ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[7]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">plt</span><span class="o">.</span><span class="n">figure</span><span class="p">(</span><span class="n">figsize</span><span class="o">=</span><span class="p">(</span><span class="mi">20</span><span class="p">,</span><span class="mi">15</span><span class="p">))</span> 
<span class="n">ax</span> <span class="o">=</span> <span class="n">sns</span><span class="o">.</span><span class="n">countplot</span><span class="p">(</span><span class="n">x</span><span class="o">=</span><span class="s2">&quot;points&quot;</span><span class="p">,</span> <span class="n">data</span><span class="o">=</span><span class="n">wine_data</span><span class="p">)</span>
<span class="n">ax</span><span class="o">.</span><span class="n">set_xticklabels</span><span class="p">(</span><span class="n">ax</span><span class="o">.</span><span class="n">get_xticklabels</span><span class="p">(),</span><span class="n">rotation</span> <span class="o">=</span> <span class="mi">0</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedImage jp-OutputArea-output ">
<img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAABJ8AAANcCAYAAADxVg7lAAAAOXRFWHRTb2Z0d2FyZQBNYXRwbG90bGliIHZlcnNpb24zLjUuMSwgaHR0cHM6Ly9tYXRwbG90bGliLm9yZy/YYfK9AAAACXBIWXMAAAsTAAALEwEAmpwYAAA1C0lEQVR4nO3dfbRldX3n+c9XqiVqglEpjFbRXUwkdpDJg1YYOr1ipyUd6MQRNNJdToyMMiFhYRLTExNoZ8WslcUsjaZNTCIZWhEwRiT4AG0PiQRbnZlWsXzkSdpKY6QEoWxtw3SWGPA3f9zNeCjOvdwq6ntPneL1Wuuue+7v7H3u77fOvZfNu/bZp8YYAQAAAIAOj1r0BAAAAAA4dIlPAAAAALQRnwAAAABoIz4BAAAA0EZ8AgAAAKDNpkVPYKMdeeSRY9u2bYueBgAAAMAh4xOf+MRXxhib5933iItP27Zty86dOxc9DQAAAIBDRlX99Wr3edkdAAAAAG3EJwAAAADaiE8AAAAAtBGfAAAAAGgjPgEAAADQRnwCAAAAoI34BAAAAEAb8QkAAACANuITAAAAAG3EJwAAAADaiE8AAAAAtBGfAAAAAGgjPgEAAADQRnwCAAAAoI34BAAAAEAb8QkAAACANuITAAAAAG3EJwAAAADaiE8AAAAAtBGfAAAAAGgjPgEAAADQRnwCAAAAoI34BAAAAEAb8QkAAACANuITAAAAAG3EJwAAAADaiE8AAAAAtBGfAAAAAGgjPgEAAADQRnwCAAAAoI34BAAAAEAb8QkAAACANuITAAAAAG3EJwAAAADaiE8AAAAAtGmLT1V1UVXdVVU37DX+S1V1S1XdWFW/MzN+XlXtmu47eWb8WVV1/XTfG6uqpvHDq+qd0/jHqmpb11oAAAAA2D+dZz5dnOSU2YGq+qdJTk3yA2OMZyR5/TR+XJIdSZ4x7fOmqjps2u2CJGclOXb6uP8xz0zytTHG05K8IclrG9cCAAAAwH7Y1PXAY4wPzzkb6ewkrxlj3DNtc9c0fmqSy6bxW6tqV5ITquoLSY4YY3wkSarq0iSnJbl62ue3pv2vSPKHVVVjjNG1JgBYhJ9677mLnsK6/J+nvWbRUwAA4CC00dd8+r4kPza9TO5DVfUj0/iWJLfNbLd7Gtsy3d57/AH7jDHuTfL1JE+a902r6qyq2llVO/fs2XPAFgMAAADA2jY6Pm1K8oQkJyZ5ZZLLp2s41ZxtxxrjeYj7Hjg4xoVjjO1jjO2bN2/e91kDAAAAsF82Oj7tTvLuseK6JN9KcuQ0fvTMdluT3D6Nb50zntl9qmpTkscn+Wrr7AEAAADYJxsdn96b5DlJUlXfl+TRSb6S5KokO6Z3sDsmKxcWv26McUeSu6vqxOkMqZckuXJ6rKuSnDHdfmGSD7jeEwAAAMDBpe2C41X1jiQ/nuTIqtqd5NVJLkpyUVXdkOSbSc6YgtGNVXV5kpuS3JvknDHGfdNDnZ2Vd857TFYuNH71NP6WJG+bLk7+1ay8Wx4AAAAAB5HOd7t70Sp3vXiV7c9Pcv6c8Z1Jjp8z/o0kpz+cOQIAAADQa6NfdgcAAADAI4j4BAAAAEAb8QkAAACANuITAAAAAG3EJwAAAADatL3bHQBstJe+55RFT2Hd3vr8P1/0FAAAYEM48wkAAACANuITAAAAAG3EJwAAAADaiE8AAAAAtBGfAAAAAGgjPgEAAADQRnwCAAAAoI34BAAAAEAb8QkAAACANuITAAAAAG3EJwAAAADaiE8AAAAAtBGfAAAAAGgjPgEAAADQRnwCAAAAoI34BAAAAEAb8QkAAACANuITAAAAAG3EJwAAAADaiE8AAAAAtBGfAAAAAGgjPgEAAADQRnwCAAAAoI34BAAAAEAb8QkAAACANuITAAAAAG3EJwAAAADaiE8AAAAAtBGfAAAAAGgjPgEAAADQRnwCAAAAoI34BAAAAEAb8QkAAACANuITAAAAAG3EJwAAAADaiE8AAAAAtBGfAAAAAGgjPgEAAADQRnwCAAAAoI34BAAAAEAb8QkAAACANuITAAAAAG3EJwAAAADaiE8AAAAAtBGfAAAAAGgjPgEAAADQRnwCAAAAoI34BAAAAEAb8QkAAACANuITAAAAAG3EJwAAAADaiE8AAAAAtBGfAAAAAGgjPgEAAADQRnwCAAAAoI34BAAAAEAb8QkAAACANuITAAAAAG3EJwAAAADaiE8AAAAAtBGfAAAAAGgjPgEAAADQRnwCAAAAoI34BAAAAEAb8QkAAACANuITAAAAAG3EJwAAAADabFr0BAAADgXPfddbFz2FdXnfz7x00VMAAB5hnPkEAAAAQBvxCQAAAIA24hMAAAAAbcQnAAAAANqITwAAAAC0EZ8AAAAAaCM+AQAAANBGfAIAAACgjfgEAAAAQBvxCQAAAIA24hMAAAAAbcQnAAAAANqITwAAAAC0EZ8AAAAAaNMWn6rqoqq6q6pumHPfr1XVqKojZ8bOq6pdVXVLVZ08M/6sqrp+uu+NVVXT+OFV9c5p/GNVta1rLQAAAADsn84zny5Ocsreg1V1dJJ/luSLM2PHJdmR5BnTPm+qqsOmuy9IclaSY6eP+x/zzCRfG2M8Lckbkry2ZRUAAAAA7Le2+DTG+HCSr8656w1Jfj3JmBk7NcllY4x7xhi3JtmV5ISqekqSI8YYHxljjCSXJjltZp9LpttXJDnp/rOiAAAAADg4bOg1n6rqeUm+NMb4zF53bUly28zXu6exLdPtvccfsM8Y494kX0/ypFW+71lVtbOqdu7Zs+dhrwMAAACA9dmw+FRVj03yqiS/Oe/uOWNjjfG19nnw4BgXjjG2jzG2b968eT3TBQAAAOAA2Mgzn743yTFJPlNVX0iyNcknq+p7snJG09Ez225Ncvs0vnXOeGb3qapNSR6f+S/zAwAAAGBBNiw+jTGuH2McNcbYNsbYlpV49MwxxpeTXJVkx/QOdsdk5cLi140x7khyd1WdOF3P6SVJrpwe8qokZ0y3X5jkA9N1oQAAAAA4SLTFp6p6R5KPJHl6Ve2uqjNX23aMcWOSy5PclOTPk5wzxrhvuvvsJG/OykXI/yrJ1dP4W5I8qap2JflXSc5tWQgAAAAA+21T1wOPMV70EPdv2+vr85OcP2e7nUmOnzP+jSSnP7xZAgAAANBpQ9/tDgAAAIBHFvEJAAAAgDbiEwAAAABtxCcAAAAA2ohPAAAAALQRnwAAAABoIz4BAAAA0EZ8AgAAAKCN+AQAAABAG/EJAAAAgDbiEwAAAABtxCcAAAAA2ohPAAAAALQRnwAAAABoIz4BAAAA0EZ8AgAAAKCN+AQAAABAG/EJAAAAgDbiEwAAAABtxCcAAAAA2ohPAAAAALQRnwAAAABoIz4BAAAA0EZ8AgAAAKCN+AQAAABAG/EJAAAAgDbiEwAAAABtxCcAAAAA2ohPAAAAALQRnwAAAABoIz4BAAAA0EZ8AgAAAKCN+AQAAABAG/EJAAAAgDbiEwAAAABtxCcAAAAA2ohPAAAAALQRnwAAAABoIz4BAAAA0EZ8AgAAAKCN+AQAAABAG/EJAAAAgDbiEwAAAABtxCcAAAAA2ohPAAAAALQRnwAAAABoIz4BAAAA0EZ8AgAAAKCN+AQAAABAG/EJAAAAgDbiEwAAAABtxCcAAAAA2ohPAAAAALQRnwAAAABoIz4BAAAA0EZ8AgAAAKCN+AQAAABAG/EJAAAAgDbiEwAAAABtxCcAAAAA2ohPAAAAALQRnwAAAABoIz4BAAAA0EZ8AgAAAKCN+AQAAABAG/EJAAAAgDbiEwAAAABtxCcAAAAA2ohPAAAAALQRnwAAAABoIz4BAAAA0EZ8AgAAAKCN+AQAAABAG/EJAAAAgDbiEwAAAABtxCcAAAAA2ohPAAAAALQRnwAAAABoIz4BAAAA0EZ8AgAAAKCN+AQAAABAG/EJAAAAgDbiEwAAAABtxCcAAAAA2ohPAAAAALQRnwAAAABoIz4BAAAA0EZ8AgAAAKBNW3yqqouq6q6qumFm7HVV9bmq+mxVvaeqvnvmvvOqaldV3VJVJ8+MP6uqrp/ue2NV1TR+eFW9cxr/WFVt61oLAAAAAPun88yni5OcstfYNUmOH2P8QJL/lOS8JKmq45LsSPKMaZ83VdVh0z4XJDkrybHTx/2PeWaSr40xnpbkDUle27YSAAAAAPZLW3waY3w4yVf3Gnv/GOPe6cuPJtk63T41yWVjjHvGGLcm2ZXkhKp6SpIjxhgfGWOMJJcmOW1mn0um21ckOen+s6IAAAAAODgs8ppPL0ty9XR7S5LbZu7bPY1tmW7vPf6Afaag9fUkT5r3jarqrKraWVU79+zZc8AWAAAAAMDaFhKfqupVSe5N8vb7h+ZsNtYYX2ufBw+OceEYY/sYY/vmzZv3dboAAAAA7KcNj09VdUaS5yb52emldMnKGU1Hz2y2Ncnt0/jWOeMP2KeqNiV5fPZ6mR8AAAAAi7Wh8amqTknyG0meN8b425m7rkqyY3oHu2OycmHx68YYdyS5u6pOnK7n9JIkV87sc8Z0+4VJPjATswAAAAA4CGzqeuCqekeSH09yZFXtTvLqrLy73eFJrpmuDf7RMcYvjjFurKrLk9yUlZfjnTPGuG96qLOz8s55j8nKNaLuv07UW5K8rap2ZeWMpx1dawEAAABg/7TFpzHGi+YMv2WN7c9Pcv6c8Z1Jjp8z/o0kpz+cOQIAAADQa5HvdgcAAADAIU58AgAAAKCN+AQAAABAG/EJAAAAgDbiEwAAAABtxCcAAAAA2mxa9AQAWIzXXnbyoqewbr+x4y8WPQUAAGA/OfMJAAAAgDbiEwAAAABtxCcAAAAA2ohPAAAAALQRnwAAAABoIz4BAAAA0EZ8AgAAAKCN+AQAAABAG/EJAAAAgDbiEwAAAABtxCcAAAAA2ohPAAAAALQRnwAAAABoIz4BAAAA0EZ8AgAAAKCN+AQAAABAG/EJAAAAgDbiEwAAAABtxCcAAAAA2ohPAAAAALTZtOgJAACPPD/97t9b9BTW5d+/4BWLngIAwNJz5hMAAAAAbcQnAAAAANqITwAAAAC0EZ8AAAAAaCM+AQAAANBGfAIAAACgjfgEAAAAQBvxCQAAAIA24hMAAAAAbcQnAAAAANqITwAAAAC0EZ8AAAAAaCM+AQAAANBGfAIAAACgjfgEAAAAQBvxCQAAAIA24hMAAAAAbcQnAAAAANqITwAAAAC0EZ8AAAAAaCM+AQAAANBGfAIAAACgjfgEAAAAQBvxCQAAAIA24hMAAAAAbcQnAAAAANqITwAAAAC0EZ8AAAAAaCM+AQAAANBGfAIAAACgjfgEAAAAQBvxCQAAAIA24hMAAAAAbcQnAAAAANqITwAAAAC0EZ8AAAAAaLNp0RMAAODg9Nwr/mzRU1iX973w9EVPAQBYgzOfAAAAAGgjPgEAAADQRnwCAAAAoI34BAAAAEAb8QkAAACANuITAAAAAG3EJwAAAADaiE8AAAAAtBGfAAAAAGgjPgEAAADQRnwCAAAAoI34BAAAAEAb8QkAAACANuITAAAAAG3EJwAAAADaiE8AAAAAtBGfAAAAAGgjPgEAAADQRnwCAAAAoI34BAAAAEAb8QkAAACANuITAAAAAG3EJwAAAADatMWnqrqoqu6qqhtmxp5YVddU1eenz0+Yue+8qtpVVbdU1ckz48+qquun+95YVTWNH15V75zGP1ZV27rWAgAAAMD+6Tzz6eIkp+w1dm6Sa8cYxya5dvo6VXVckh1JnjHt86aqOmza54IkZyU5dvq4/zHPTPK1McbTkrwhyWvbVgIAAADAfmmLT2OMDyf56l7Dpya5ZLp9SZLTZsYvG2PcM8a4NcmuJCdU1VOSHDHG+MgYYyS5dK997n+sK5KcdP9ZUQAAAAAcHDb6mk9PHmPckSTT56Om8S1JbpvZbvc0tmW6vff4A/YZY9yb5OtJnjTvm1bVWVW1s6p27tmz5wAtBQAAAICHcrBccHzeGUtjjfG19nnw4BgXjjG2jzG2b968eT+nCAAAAMC+2uj4dOf0UrpMn++axncnOXpmu61Jbp/Gt84Zf8A+VbUpyePz4Jf5AQAAALBAGx2frkpyxnT7jCRXzozvmN7B7pisXFj8uumleXdX1YnT9Zxestc+9z/WC5N8YLouFAAAAAAHiU1dD1xV70jy40mOrKrdSV6d5DVJLq+qM5N8McnpSTLGuLGqLk9yU5J7k5wzxrhveqizs/LOeY9JcvX0kSRvSfK2qtqVlTOednStBQAAAID90xafxhgvWuWuk1bZ/vwk588Z35nk+Dnj38gUrwAAAAA4OB0sFxwHAAAA4BAkPgEAAADQRnwCAAAAoI34BAAAAEAb8QkAAACANuITAAAAAG3EJwAAAADaiE8AAAAAtBGfAAAAAGgjPgEAAADQRnwCAAAAoI34BAAAAEAb8QkAAACANuITAAAAAG3EJwAAAADaiE8AAAAAtBGfAAAAAGgjPgEAAADQRnwCAAAAoI34BAAAAEAb8QkAAACANuITAAAAAG3EJwAAAADaiE8AAAAAtBGfAAAAAGgjPgEAAADQRnwCAAAAoI34BAAAAEAb8QkAAACANuITAAAAAG3EJwAAAADaiE8AAAAAtBGfAAAAAGgjPgEAAADQRnwCAAAAoI34BAAAAEAb8QkAAACANuITAAAAAG3EJwAAAADaiE8AAAAAtBGfAAAAAGgjPgEAAADQRnwCAAAAoI34BAAAAEAb8QkAAACANuITAAAAAG3EJwAAAADabFr0BACWwVsu/clFT2HdznzJ+xc9BQAAgP+fM58AAAAAaOPMJwAAHjFOveIvFj2FdbvyhScvegoAcEA48wkAAACANuITAAAAAG3EJwAAAADaiE8AAAAAtBGfAAAAAGgjPgEAAADQRnwCAAAAoI34BAAAAEAb8QkAAACANuITAAAAAG3WFZ+q6tr1jAEAAADArE1r3VlV35HksUmOrKonJKnpriOSPLV5bgAAAAAsuTXjU5JfSPKKrISmT+Tb8elvkvxR37QAAAAAOBSsGZ/GGL+f5Per6pfGGH+wQXMCAAAA4BDxUGc+JUnGGH9QVT+aZNvsPmOMS5vmBQAAAMAhYF3xqareluR7k3w6yX3T8EgiPgEAAACwqnXFpyTbkxw3xhidkwEAAADg0PKodW53Q5Lv6ZwIAAAAAIee9Z75dGSSm6rquiT33D84xnhey6wAAAAAOCSsNz79VuckAAAAADg0rffd7j7UPREAAAAADj3rfbe7u7Py7nZJ8ugkfy/JfxtjHNE1MQAAAACW33rPfPqu2a+r6rQkJ3RMCAAAAIBDx3rf7e4BxhjvTfKcAzsVAAAAAA41633Z3QtmvnxUku359svwAAAAAGCu9b7b3f84c/veJF9IcuoBnw0AAAAAh5T1XvPppd0TAQAAAODQs65rPlXV1qp6T1XdVVV3VtW7qmpr9+QAAAAAWG7rveD4W5NcleSpSbYk+XfTGAAAAACsar3xafMY461jjHunj4uTbG6cFwAAAACHgPXGp69U1Yur6rDp48VJ/kvnxAAAAABYfuuNTy9L8i+SfDnJHUlemMRFyAEAAABY07re7S7Jbyc5Y4zxtSSpqicmeX1WohQAAAAAzLXeM59+4P7wlCRjjK8m+eGeKQEAAABwqFhvfHpUVT3h/i+mM5/We9YUAAAAAI9Q6w1Iv5vkP1bVFUlGVq7/dH7brAAAAAA4JKwrPo0xLq2qnUmek6SSvGCMcVPrzAAAAABYeut+6dwUmwQnAAAAANZtvdd8OqCq6ler6saquqGq3lFV31FVT6yqa6rq89Pn2WtMnVdVu6rqlqo6eWb8WVV1/XTfG6uqFrEeAAAAAObb8PhUVVuS/HKS7WOM45MclmRHknOTXDvGODbJtdPXqarjpvufkeSUJG+qqsOmh7sgyVlJjp0+TtnApQAAAADwEBZy5lNWXu73mKralOSxSW5PcmqSS6b7L0ly2nT71CSXjTHuGWPcmmRXkhOq6ilJjhhjfGSMMZJcOrMPAAAAAAeBDY9PY4wvJXl9ki8muSPJ18cY70/y5DHGHdM2dyQ5atplS5LbZh5i9zS2Zbq99/iDVNVZVbWzqnbu2bPnQC4HAAAAgDUs4mV3T8jK2UzHJHlqksdV1YvX2mXO2Fhj/MGDY1w4xtg+xti+efPmfZ0yAAAAAPtpES+7+4kkt44x9owx/i7Ju5P8aJI7p5fSZfp817T97iRHz+y/NSsv09s93d57HAAAAICDxCLi0xeTnFhVj53ene6kJDcnuSrJGdM2ZyS5crp9VZIdVXV4VR2TlQuLXze9NO/uqjpxepyXzOwDAAAAwEFg00Z/wzHGx6rqiiSfTHJvkk8luTDJdya5vKrOzEqgOn3a/saqujzJTdP254wx7pse7uwkFyd5TJKrpw8AAAAADhIbHp+SZIzx6iSv3mv4nqycBTVv+/OTnD9nfGeS4w/4BAEAAAA4IBbxsjsAAAAAHiHEJwAAAADaiE8AAAAAtBGfAAAAAGgjPgEAAADQRnwCAAAAoI34BAAAAEAb8QkAAACANuITAAAAAG3EJwAAAADaiE8AAAAAtBGfAAAAAGgjPgEAAADQRnwCAAAAoI34BAAAAEAb8QkAAACANuITAAAAAG3EJwAAAADaiE8AAAAAtBGfAAAAAGgjPgEAAADQRnwCAAAAoI34BAAAAEAb8QkAAACANuITAAAAAG3EJwAAAADaiE8AAAAAtBGfAAAAAGgjPgEAAADQRnwCAAAAoI34BAAAAEAb8QkAAACANuITAAAAAG3EJwAAAADaiE8AAAAAtBGfAAAAAGgjPgEAAADQRnwCAAAAoI34BAAAAEAb8QkAAACANuITAAAAAG3EJwAAAADaiE8AAAAAtBGfAAAAAGgjPgEAAADQRnwCAAAAoI34BAAAAEAb8QkAAACANuITAAAAAG3EJwAAAADaiE8AAAAAtBGfAAAAAGgjPgEAAADQRnwCAAAAoI34BAAAAEAb8QkAAACANuITAAAAAG3EJwAAAADaiE8AAAAAtBGfAAAAAGgjPgEAAADQRnwCAAAAoI34BAAAAEAb8QkAAACANuITAAAAAG3EJwAAAADaiE8AAAAAtBGfAAAAAGgjPgEAAADQRnwCAAAAoI34BAAAAEAb8QkAAACANuITAAAAAG3EJwAAAADaiE8AAAAAtBGfAAAAAGgjPgEAAADQRnwCAAAAoI34BAAAAEAb8QkAAACANuITAAAAAG3EJwAAAADaiE8AAAAAtBGfAAAAAGgjPgEAAADQRnwCAAAAoM2mRU8AOPS896J/vugprMtpL7t60VMAAAA45DnzCQAAAIA2C4lPVfXdVXVFVX2uqm6uqn9UVU+sqmuq6vPT5yfMbH9eVe2qqluq6uSZ8WdV1fXTfW+sqlrEegAAAACYb1FnPv1+kj8fY/zDJD+Y5OYk5ya5doxxbJJrp69TVccl2ZHkGUlOSfKmqjpsepwLkpyV5Njp45SNXAQAAAAAa9vw+FRVRyR5dpK3JMkY45tjjP+a5NQkl0ybXZLktOn2qUkuG2PcM8a4NcmuJCdU1VOSHDHG+MgYYyS5dGYfAAAAAA4Cizjz6b9LsifJW6vqU1X15qp6XJInjzHuSJLp81HT9luS3Daz/+5pbMt0e+/xB6mqs6pqZ1Xt3LNnz4FdDQAAAACrWkR82pTkmUkuGGP8cJL/lukldquYdx2nscb4gwfHuHCMsX2MsX3z5s37Ol8AAAAA9tMi4tPuJLvHGB+bvr4iKzHqzumldJk+3zWz/dEz+29Ncvs0vnXOOAAAAAAHiU0b/Q3HGF+uqtuq6uljjFuSnJTkpunjjCSvmT5fOe1yVZI/rap/k+SpWbmw+HVjjPuq6u6qOjHJx5K8JMkfbPByAABgoX7mXR9f9BTW7V0/8yOLngIAC7Dh8WnyS0neXlWPTvKfk7w0K2dhXV5VZyb5YpLTk2SMcWNVXZ6VOHVvknPGGPdNj3N2kouTPCbJ1dMHAAAAAAeJhcSnMcank2yfc9dJq2x/fpLz54zvTHL8AZ0cAAAAAAfMIq75BAAAAMAjhPgEAAAAQBvxCQAAAIA24hMAAAAAbcQnAAAAANqITwAAAAC0EZ8AAAAAaCM+AQAAANBGfAIAAACgjfgEAAAAQBvxCQAAAIA24hMAAAAAbcQnAAAAANqITwAAAAC0EZ8AAAAAaCM+AQAAANBGfAIAAACgjfgEAAAAQBvxCQAAAIA24hMAAAAAbcQnAAAAANqITwAAAAC0EZ8AAAAAaCM+AQAAANBGfAIAAACgjfgEAAAAQBvxCQAAAIA24hMAAAAAbcQnAAAAANqITwAAAAC0EZ8AAAAAaCM+AQAAANBGfAIAAACgjfgEAAAAQBvxCQAAAIA24hMAAAAAbcQnAAAAANqITwAAAAC0EZ8AAAAAaCM+AQAAANBGfAIAAACgjfgEAAAAQBvxCQAAAIA24hMAAAAAbcQnAAAAANqITwAAAAC0EZ8AAAAAaCM+AQAAANBGfAIAAACgjfgEAAAAQBvxCQAAAIA24hMAAAAAbcQnAAAAANqITwAAAAC0EZ8AAAAAaCM+AQAAANBGfAIAAACgjfgEAAAAQBvxCQAAAIA24hMAAAAAbcQnAAAAANqITwAAAAC0EZ8AAAAAaCM+AQAAANBGfAIAAACgjfgEAAAAQBvxCQAAAIA24hMAAAAAbcQnAAAAANqITwAAAAC0EZ8AAAAAaCM+AQAAANBGfAIAAACgjfgEAAAAQBvxCQAAAIA24hMAAAAAbcQnAAAAANqITwAAAAC0EZ8AAAAAaCM+AQAAANBGfAIAAACgjfgEAAAAQBvxCQAAAIA24hMAAAAAbcQnAAAAANqITwAAAAC0EZ8AAAAAaCM+AQAAANBmYfGpqg6rqk9V1fumr59YVddU1eenz0+Y2fa8qtpVVbdU1ckz48+qquun+95YVbWItQAAAAAw3yLPfPqVJDfPfH1ukmvHGMcmuXb6OlV1XJIdSZ6R5JQkb6qqw6Z9LkhyVpJjp49TNmbqAAAAAKzHQuJTVW1N8tNJ3jwzfGqSS6bblyQ5bWb8sjHGPWOMW5PsSnJCVT0lyRFjjI+MMUaSS2f2AQAAAOAgsKgzn34vya8n+dbM2JPHGHckyfT5qGl8S5LbZrbbPY1tmW7vPf4gVXVWVe2sqp179uw5IAsAAAAA4KFteHyqqucmuWuM8Yn17jJnbKwx/uDBMS4cY2wfY2zfvHnzOr8tAAAAAA/XpgV8z3+c5HlV9VNJviPJEVX1J0nurKqnjDHumF5Sd9e0/e4kR8/svzXJ7dP41jnjAAAAABwkNvzMpzHGeWOMrWOMbVm5kPgHxhgvTnJVkjOmzc5IcuV0+6okO6rq8Ko6JisXFr9uemne3VV14vQudy+Z2QcAAACAg8AiznxazWuSXF5VZyb5YpLTk2SMcWNVXZ7kpiT3JjlnjHHftM/ZSS5O8pgkV08fAAAAABwkFhqfxhgfTPLB6fZ/SXLSKtudn+T8OeM7kxzfN0MAAAAAHo5FvdsdAAAAAI8A4hMAAAAAbcQnAAAAANqITwAAAAC0EZ8AAAAAaCM+AQAAANBGfAIAAACgjfgEAAAAQBvxCQAAAIA24hMAAAAAbcQnAAAAANqITwAAAAC0EZ8AAAAAaCM+AQAAANBGfAIAAACgjfgEAAAAQBvxCQAAAIA24hMAAAAAbcQnAAAAANqITwAAAAC0EZ8AAAAAaLNp0RMAAACY9cvvuW3RU1i3Nz7/6EVPAeCg58wnAAAAANqITwAAAAC0EZ8AAAAAaCM+AQAAANBGfAIAAACgjfgEAAAAQBvxCQAAAIA24hMAAAAAbcQnAAAAANqITwAAAAC0EZ8AAAAAaCM+AQAAANBGfAIAAACgjfgEAAAAQBvxCQAAAIA24hMAAAAAbcQnAAAAANqITwAAAAC0EZ8AAAAAaCM+AQAAANBGfAIAAACgjfgEAAAAQBvxCQAAAIA24hMAAAAAbcQnAAAAANqITwAAAAC02bToCcAj3f/1b5+76Cmsy4/9/PsWPQUAAACWkDOfAAAAAGgjPgEAAADQRnwCAAAAoI34BAAAAEAb8QkAAACANuITAAAAAG3EJwAAAADaiE8AAAAAtBGfAAAAAGgjPgEAAADQRnwCAAAAoI34BAAAAEAb8QkAAACANuITAAAAAG3EJwAAAADaiE8AAAAAtBGfAAAAAGgjPgEAAADQRnwCAAAAoI34BAAAAEAb8QkAAACANuITAAAAAG3EJwAAAADaiE8AAAAAtBGfAAAAAGgjPgEAAADQRnwCAAAAoI34BAAAAEAb8QkAAACANuITAAAAAG3EJwAAAADaiE8AAAAAtBGfAAAAAGgjPgEAAADQRnwCAAAAoI34BAAAAEAb8QkAAACANuITAAAAAG3EJwAAAADabHh8qqqjq+o/VNXNVXVjVf3KNP7Eqrqmqj4/fX7CzD7nVdWuqrqlqk6eGX9WVV0/3ffGqqqNXg8AAAAAq1vEmU/3Jvlfxxjfn+TEJOdU1XFJzk1y7Rjj2CTXTl9num9HkmckOSXJm6rqsOmxLkhyVpJjp49TNnIhAAAAAKxtw+PTGOOOMcYnp9t3J7k5yZYkpya5ZNrskiSnTbdPTXLZGOOeMcatSXYlOaGqnpLkiDHGR8YYI8mlM/sAAAAAcBBY6DWfqmpbkh9O8rEkTx5j3JGsBKokR02bbUly28xuu6exLdPtvcfnfZ+zqmpnVe3cs2fPAV0DAAAAAKtbWHyqqu9M8q4krxhj/M1am84ZG2uMP3hwjAvHGNvHGNs3b96875MFAAAAYL8sJD5V1d/LSnh6+xjj3dPwndNL6TJ9vmsa353k6Jndtya5fRrfOmccAAAAgIPEIt7trpK8JcnNY4x/M3PXVUnOmG6fkeTKmfEdVXV4VR2TlQuLXze9NO/uqjpxesyXzOwDAAAAwEFg0wK+5z9O8nNJrq+qT09j/zrJa5JcXlVnJvliktOTZIxxY1VdnuSmrLxT3jljjPum/c5OcnGSxyS5evoAAAAA4CCx4fFpjPF/Z/71mpLkpFX2OT/J+XPGdyY5/sDNDgAAAIADaaHvdgcAAADAoU18AgAAAKCN+AQAAABAG/EJAAAAgDbiEwAAAABtNvzd7uDh+PwfnrroKazLsS+/ctFTAAAAgIOCM58AAAAAaCM+AQAAANBGfAIAAACgjfgEAAAAQBvxCQAAAIA24hMAAAAAbcQnAAAAANqITwAAAAC0EZ8AAAAAaCM+AQAAANBGfAIAAACgjfgEAAAAQBvxCQAAAIA24hMAAAAAbcQnAAAAANqITwAAAAC0EZ8AAAAAaLNp0RMAAAB4JLjk3XsWPYV1OeMFmxc9BeAQ48wnAAAAANqITwAAAAC0EZ8AAAAAaCM+AQAAANBGfAIAAACgjfgEAAAAQBvxCQAAAIA24hMAAAAAbcQnAAAAANqITwAAAAC0EZ8AAAAAaCM+AQAAANBGfAIAAACgjfgEAAAAQBvxCQAAAIA24hMAAAAAbcQnAAAAANqITwAAAAC0EZ8AAAAAaCM+AQAAANBGfAIAAACgjfgEAAAAQBvxCQAAAIA24hMAAAAAbcQnAAAAANqITwAAAAC0EZ8AAAAAaCM+AQAAANBGfAIAAACgjfgEAAAAQBvxCQAAAIA24hMAAAAAbcQnAAAAANqITwAAAAC02bToCdDnzgv+90VPYV2efPa/XvQUAAAAgCbOfAIAAACgjfgEAAAAQBvxCQAAAIA24hMAAAAAbcQnAAAAANqITwAAAAC0EZ8AAAAAaCM+AQAAANBm06InAAAAwHK69k/3LHoK63LS/7R50VOARzRnPgEAAADQRnwCAAAAoI34BAAAAEAb8QkAAACANi44nmTPBX+y6Cms2+azX7zoKQAAAACsmzOfAAAAAGgjPgEAAADQRnwCAAAAoI34BAAAAEAb8QkAAACANuITAAAAAG3EJwAAAADaiE8AAAAAtNm06AkAAADAweKG/+PORU9hXY7/hScvegqwbs58AgAAAKCN+AQAAABAG/EJAAAAgDbiEwAAAABtxCcAAAAA2ni3OwAAADiEffl1f73oKazL97zyHyx6CjRZ+jOfquqUqrqlqnZV1bmLng8AAAAA37bUZz5V1WFJ/ijJP0uyO8nHq+qqMcZNi50ZAAAA0OXO3/v4oqewbk9+xY8segoLt9TxKckJSXaNMf5zklTVZUlOTSI+AQAAAEvjrj/8i0VPYd2OevnJ+7R9jTGaptKvql6Y5JQxxv8yff1zSf6HMcbL99rurCRnTV8+PcktGzTFI5N8ZYO+10axpuVgTcvhUFxTcmiuy5qWgzUtB2taHofiuqxpOVjTcrCm5bFR6/oHY4zN8+5Y9jOfas7Yg2raGOPCJBf2T+eBqmrnGGP7Rn/fTta0HKxpORyKa0oOzXVZ03KwpuVgTcvjUFyXNS0Ha1oO1rQ8DoZ1LfsFx3cnOXrm661Jbl/QXAAAAADYy7LHp48nObaqjqmqRyfZkeSqBc8JAAAAgMlSv+xujHFvVb08yV8kOSzJRWOMGxc8rVkb/lK/DWBNy8GalsOhuKbk0FyXNS0Ha1oO1rQ8DsV1WdNysKblYE3LY+HrWuoLjgMAAABwcFv2l90BAAAAcBATnwAAAABoIz4dIFX1q1V1Y1XdUFXvqKrvqKonVtU1VfX56fMTFj3PfbHKmk6fxr5VVUv3FpSrrOl1VfW5qvpsVb2nqr570fPcF6us6ben9Xy6qt5fVU9d9Dz3xbw1zdz3a1U1qurIRc5xf6zyXP1WVX1peq4+XVU/teh57ovVnquq+qWqumW673cWPc99scrz9M6Z5+gLVfXpRc9zX6yyph+qqo9Oa9pZVScsep77YpU1/WBVfaSqrq+qf1dVRyx6nvuiqn5lWs+NVfWKaWzZjyXmrWmpjyWSVde17McT89a07McTD1rTzH1LeTyxyvO07McSc5+nJT+WmPc8LfuxxLw1LfWxRLLqupbqeKKqLqqqu6rqhpmxVY8fquq8qto1/X6dvGETHWP4eJgfSbYkuTXJY6avL0/yPyf5nSTnTmPnJnntoud6ANb0/UmenuSDSbYvep4HaE0/mWTTNPbaQ+R5OmJmm19O8seLnuvDXdN0++isvMHAXyc5ctFzPUDP1W8l+bVFz+8Ar+mfJvnLJIdP40cteq4Pd017bfO7SX5z0XM9AM/T+5P882nsp5J8cNFzPQBr+niSfzKNvSzJby96rvuwpuOT3JDksVl5Q5i/THLskh9LrLampT2WeIh1LfPxxGprWubjiblrmu5byuOJNZ6nZT6WWG1Ny3wsserP3sw2y3YssdrztLTHEg+xrqU6nkjy7CTPTHLDzNjc44ckxyX5TJLDkxyT5K+SHLYR83Tm04GzKcljqmpTVn54b09yapJLpvsvSXLaYqa23x60pjHGzWOMWxY8r4dj3preP8a4d7r/o0m2Lmx2+2femv5m5v7HJVm2dxaY9/uUJG9I8utZvvXcb7V1LbN5azo7yWvGGPckyRjjrgXOb3+s+jxVVSX5F0nesaC57a95axpJ7v+XvMdn+X4e563p6Uk+PN1/TZKfWdDc9sf3J/noGONvp/8mfSjJ87PcxxJz13QIHEustq5lPp5YbU3LfDyx2u9UsrzHE2utaVmttqZlPpZY83la0mOJ1da07McSq61rqY4nxhgfTvLVvYZXO344NcllY4x7xhi3JtmVZEPOWBOfDoAxxpeSvD7JF5PckeTrY4z3J3nyGOOOaZs7khy1uFnumzXWtLTWuaaXJbl6o+e2v9ZaU1WdX1W3JfnZJL+5uFnum9XWVFXPS/KlMcZnFjrB/fQQP38vn17WcNEyvaRmjTV9X5Ifq6qPVdWHqupHFjnPfbGOvxM/luTOMcbnFzG//bHGml6R5HXT34nXJzlvYZPcR2us6YYkz5s2Oz0rZzcsixuSPLuqnlRVj83KvyAfnSU+lsjqa1p261nXUh1PZI01LevxRFZZ05IfT6z1s7eUxxJZfU1LeyyRh/4bsXTHEll9Ta/Ikh5LTFZb1zIfT9xvteOHLUlum9lu9zTWTnw6AKY/8Kdm5bS1pyZ5XFW9eLGzengeiWuqqlcluTfJ2xczw3231prGGK8aYxydlfW8fHGz3DerrOklSV6V5TrofYA1nqsLknxvkh/Kyv9E/+6i5riv1ljTpiRPSHJiklcmuXz6V76D3jr+9r0oy/UvlWut6ewkvzr9nfjVJG9Z3Cz3zRprelmSc6rqE0m+K8k3FzfLfTPGuDkrL9W6JsmfZ+WU+HvX3OkgdyiuKXnodS3j8cRaa1rW44k11rS0xxNrrGlpjyXWWNPSHkus42/f0h1LrLGmpT2WSNZc19IeT6zDvN+jDTkLVHw6MH4iya1jjD1jjL9L8u4kP5rkzqp6SpJMn5fpdNHV1rTMVl1TVZ2R5LlJfnZML4ZdEut5nv40B/mponuZt6aXZuV/Mj9TVV/IyksZPllV37O4ae6zuc/VGOPOMcZ9Y4xvJfm32aDTXg+Q1X7+did591hxXZJvJVmWC7qu9XdiU5IXJHnnAue3P1Zb0xnT7ST5sxwCP3tjjM+NMX5yjPGsrBzY/9VCZ7mPxhhvGWM8c4zx7KycPv/5LPexxGprWnqrrWuJjyfW81wt2/HEvDV9IUt+PDHveVryY4nVfvaW+Vhirb8Ry3ossdqalvlYIsmqv1NLfTwxWe34YXceeCbX1mzQyyXFpwPji0lOrKrHTkX+pCQ3J7kqK7+QmT5fuaD57Y/V1rTM5q6pqk5J8htJnjfG+NuFznDfrbamY2e2eV6Szy1kdvtn3prePcY4aoyxbYyxLSt/NJ85xvjyIie6j1Z7rp4ys83zs3Ka77JY7e/Ee5M8J0mq6vuSPDrJVxY1yX201t++n0jyuTHG7oXNbv+stqbbk/yTaZvnZLmiwGq/T0clSVU9Ksn/luSPFzjHfTYz/7+flf85eUeW+1hitTUtvXnrWvLjidXWtMzHE/PWdOmyH0+s8jwt87HEan8n3pvlPZZY62/fsh5LrLamZT6WSLLq79RSH09MVjt+uCrJjqo6vKqOycoF1q/biAlt2ohvcqgbY3ysqq5I8smsnKb3qSQXJvnOrJwiemZWDpRPX9ws981qa6qq5yf5gySbk/z7qvr0GGPj3p7xYVjjeboxK1f7v2Y6m/ejY4xfXNhE98Eaa/rTqnp6Vv6V6K+TLMV6kjXXtNTWWNebq+qHsnK66xeS/MKi5riv1ljTSHJRrbzd6zeTnLEsZwA8xM/fjizh/zivsaZPJfn96V9hv5HkrMXNct+ssaZfrKpzps3eneStC5ri/npXVT0pyd8lOWeM8bWqek2W9FhiMm9NS3ssMWPeuv4wS3o8MZm3pjcv6/HE5EFrWvSEDoB5z9PblvVYYjJvTRdlSY8lJqv97C3lscRk3vP081nSY4kZ89b1K8t0PFFV70jy40mOrKrdSV6dZO7xwxjjxqq6PMlNWTmGOmeMcd+GzHO5focBAAAAWCZedgcAAABAG/EJAAAAgDbiEwAAAABtxCcAAAAA2ohPAAAAALQRnwAADjLTW9wf9xDbnPZQ2wAAHAxqjLHoOQAAsI+q6uIk7xtjXLHouQAArMWZTwAAzapqW1V9rqouqarPVtUVVfXYqjqpqj5VVddX1UVVdfi0/Qeravt0+/+tqvOr6jNV9dGqenJV/WiS5yV5XVV9uqq+t6p+uapumh7/skWuFwBglvgEALAxnp7kwjHGDyT5myT/KsnFSf7lGOO/T7Ipydlz9ntcko+OMX4wyYeT/PwY4z8muSrJK8cYPzTG+Ksk5yb54enxf7F9NQAA6yQ+AQBsjNvGGP/PdPtPkpyU5NYxxn+axi5J8uw5+30zyfum259Ism2Vx/9skrdX1YuT3HtAZgwAcACITwAAG2N/L7T5d+PbF+m8LytnSM3z00n+KMmzknyiqlbbDgBgQ4lPAAAb4+9X1T+abr8oyV8m2VZVT5vGfi7Jh/bh8e5O8l1JUlWPSnL0GOM/JPn1JN+d5DsPxKQBAB4u8QkAYGPcnOSMqvpskicmeUOSlyb5s6q6Psm3kvzxPjzeZUleWVWfSnJskj+ZHudTSd4wxvivB3LyAAD7q759FjcAAB2qaluS940xjl/0XAAANpoznwAAAABo48wnAAAAANo48wkAAACANuITAAAAAG3EJwAAAADaiE8AAAAAtBGfAAAAAGjz/wHdMLaBf1iMCwAAAABJRU5ErkJggg==
"
>
</div>

</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[8]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Analyze Stats for Price</span>
<span class="n">mean</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">mean</span><span class="p">(</span><span class="n">wine_data</span><span class="p">[</span><span class="s1">&#39;points&#39;</span><span class="p">])</span>
<span class="n">median</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">median</span><span class="p">(</span><span class="n">wine_data</span><span class="p">[</span><span class="s1">&#39;points&#39;</span><span class="p">])</span>
<span class="n">mini</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">min</span><span class="p">(</span><span class="n">wine_data</span><span class="p">[</span><span class="s1">&#39;points&#39;</span><span class="p">])</span>
<span class="n">maxi</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">max</span><span class="p">(</span><span class="n">wine_data</span><span class="p">[</span><span class="s1">&#39;points&#39;</span><span class="p">])</span>
<span class="n">stddev</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">std</span><span class="p">(</span><span class="n">wine_data</span><span class="p">[</span><span class="s1">&#39;points&#39;</span><span class="p">])</span>

<span class="nb">print</span><span class="p">(</span><span class="s1">&#39;SUMMARY STATS FOR POINTS OF WINE IN THE DATASET&#39;</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="s1">&#39;Mean: &#39;</span><span class="p">,</span> <span class="n">mean</span><span class="p">,</span> <span class="s1">&#39;</span><span class="se">\n</span><span class="s1">Std Dev: &#39;</span><span class="p">,</span> <span class="n">stddev</span><span class="p">,</span> <span class="s1">&#39;</span><span class="se">\n</span><span class="s1">Median: &#39;</span><span class="p">,</span> <span class="n">median</span><span class="p">,</span> <span class="s1">&#39;</span><span class="se">\n</span><span class="s1">Min: &#39;</span><span class="p">,</span> <span class="n">mini</span><span class="p">,</span> <span class="s1">&#39;</span><span class="se">\n</span><span class="s1">Max: &#39;</span><span class="p">,</span> <span class="n">maxi</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>


<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="text/plain">
<pre>SUMMARY STATS FOR POINTS OF WINE IN THE DATASET
Mean:  88.42188055383343 
Std Dev:  3.044495379452498 
Median:  88.0 
Min:  80 
Max:  100
</pre>
</div>
</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[&nbsp;]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span> 
</pre></div>

     </div>
</div>
</div>
</div>

</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><strong>As we can see, we have a pretty mixed dataset. Most of the wine is from the US, followed by France, Italy, Spain, and Portugal. However, we can see that there are a lot of different countries in our dataset. The points of the data set follow a fairly normal distribution centered around between 87 and 89 points. We can see that there are a lot of bottles in the 84-93 range and the values outside that range drop as they get further away from that range. There are a lot of wine prices in our datset, but the average is around x. The highest priced wine bottle in this dataset is x and the cheapest is x.</strong></p>

</div>
</div>
</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><strong>Hypothesis Testing</strong></p>

</div>
</div>
</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>To start this part of the process, I first want to examine some of the correlation</p>

</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[9]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">wine_data</span><span class="o">.</span><span class="n">corr</span><span class="p">()</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt">Out[9]:</div>



<div class="jp-RenderedHTMLCommon jp-RenderedHTML jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/html">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>points</th>
      <th>price</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>points</th>
      <td>1.000000</td>
      <td>0.416167</td>
    </tr>
    <tr>
      <th>price</th>
      <td>0.416167</td>
      <td>1.000000</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[10]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">less_than_100</span> <span class="o">=</span> <span class="n">wine_data</span><span class="p">[</span><span class="n">wine_data</span><span class="p">[</span><span class="s2">&quot;price&quot;</span><span class="p">]</span> <span class="o">&lt;=</span> <span class="mi">100</span><span class="p">]</span>
<span class="n">less_than_100</span><span class="o">.</span><span class="n">corr</span><span class="p">()</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt">Out[10]:</div>



<div class="jp-RenderedHTMLCommon jp-RenderedHTML jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/html">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>points</th>
      <th>price</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>points</th>
      <td>1.000000</td>
      <td>0.548092</td>
    </tr>
    <tr>
      <th>price</th>
      <td>0.548092</td>
      <td>1.000000</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[11]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">less_than_50</span> <span class="o">=</span> <span class="n">wine_data</span><span class="p">[</span><span class="n">wine_data</span><span class="p">[</span><span class="s2">&quot;price&quot;</span><span class="p">]</span> <span class="o">&lt;=</span> <span class="mi">50</span><span class="p">]</span>
<span class="n">less_than_50</span><span class="o">.</span><span class="n">corr</span><span class="p">()</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt">Out[11]:</div>



<div class="jp-RenderedHTMLCommon jp-RenderedHTML jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/html">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>points</th>
      <th>price</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>points</th>
      <td>1.000000</td>
      <td>0.497463</td>
    </tr>
    <tr>
      <th>price</th>
      <td>0.497463</td>
      <td>1.000000</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[12]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># store the feature matrix (X) and response vector (y)</span>
<span class="n">x</span> <span class="o">=</span> <span class="n">wine_data</span><span class="p">[</span><span class="s1">&#39;price&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">values</span><span class="o">.</span><span class="n">reshape</span><span class="p">(</span><span class="o">-</span><span class="mi">1</span><span class="p">,</span><span class="mi">1</span><span class="p">)</span>
<span class="n">y</span> <span class="o">=</span> <span class="n">wine_data</span><span class="p">[</span><span class="s1">&#39;points&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">values</span><span class="o">.</span><span class="n">reshape</span><span class="p">(</span><span class="o">-</span><span class="mi">1</span><span class="p">,</span><span class="mi">1</span><span class="p">)</span>

<span class="nb">print</span><span class="p">(</span><span class="n">x</span><span class="o">.</span><span class="n">size</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="n">y</span><span class="o">.</span><span class="n">size</span><span class="p">)</span>

<span class="c1">#Ensure both equal each other and match up</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>


<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="text/plain">
<pre>120975
120975
</pre>
</div>
</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[13]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">import</span> <span class="nn">numpy</span> <span class="k">as</span> <span class="nn">np</span>
<span class="kn">from</span> <span class="nn">sklearn.linear_model</span> <span class="kn">import</span> <span class="n">LinearRegression</span>


<span class="n">linear_regressor</span> <span class="o">=</span> <span class="n">LinearRegression</span><span class="p">()</span>  <span class="c1"># create object for the class</span>
<span class="n">linear_regressor</span><span class="o">.</span><span class="n">fit</span><span class="p">(</span><span class="n">x</span><span class="p">,</span> <span class="n">y</span><span class="p">)</span>  <span class="c1"># perform linear regression</span>
<span class="n">Y_pred</span> <span class="o">=</span> <span class="n">linear_regressor</span><span class="o">.</span><span class="n">predict</span><span class="p">(</span><span class="n">x</span><span class="p">)</span>  
</pre></div>

     </div>
</div>
</div>
</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[14]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">plt</span><span class="o">.</span><span class="n">scatter</span><span class="p">(</span><span class="n">x</span><span class="p">,</span> <span class="n">y</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">x</span><span class="p">,</span> <span class="n">Y_pred</span><span class="p">,</span> <span class="n">color</span><span class="o">=</span><span class="s1">&#39;red&#39;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedImage jp-OutputArea-output ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>

</div>

</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>In this case we can see that a simple linear regression model may not make sense for all of the data points, However let's attempt it for the miniture data set we created earlier.</p>

</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[15]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">x1</span> <span class="o">=</span> <span class="n">less_than_100</span><span class="p">[</span><span class="s1">&#39;price&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">values</span><span class="o">.</span><span class="n">reshape</span><span class="p">(</span><span class="o">-</span><span class="mi">1</span><span class="p">,</span><span class="mi">1</span><span class="p">)</span>
<span class="n">y1</span> <span class="o">=</span> <span class="n">less_than_100</span><span class="p">[</span><span class="s1">&#39;points&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">values</span><span class="o">.</span><span class="n">reshape</span><span class="p">(</span><span class="o">-</span><span class="mi">1</span><span class="p">,</span><span class="mi">1</span><span class="p">)</span>

<span class="n">linear_regressor</span> <span class="o">=</span> <span class="n">LinearRegression</span><span class="p">()</span>  <span class="c1"># create object for the class</span>
<span class="n">linear_regressor</span><span class="o">.</span><span class="n">fit</span><span class="p">(</span><span class="n">x1</span><span class="p">,</span> <span class="n">y1</span><span class="p">)</span>  <span class="c1"># perform linear regression</span>
<span class="n">Y_pred</span> <span class="o">=</span> <span class="n">linear_regressor</span><span class="o">.</span><span class="n">predict</span><span class="p">(</span><span class="n">x1</span><span class="p">)</span>  
<span class="n">plt</span><span class="o">.</span><span class="n">scatter</span><span class="p">(</span><span class="n">x1</span><span class="p">,</span> <span class="n">y1</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">x1</span><span class="p">,</span> <span class="n">Y_pred</span><span class="p">,</span> <span class="n">color</span><span class="o">=</span><span class="s1">&#39;red&#39;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedImage jp-OutputArea-output ">
<img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAYAAAAD4CAYAAADlwTGnAAAAOXRFWHRTb2Z0d2FyZQBNYXRwbG90bGliIHZlcnNpb24zLjUuMSwgaHR0cHM6Ly9tYXRwbG90bGliLm9yZy/YYfK9AAAACXBIWXMAAAsTAAALEwEAmpwYAAA0X0lEQVR4nO2de5xUxZn3v8/0zMAMggMIREAEEe+IFyIgChplJWAiGhMhouSm2TfJGxMirCx51zXxMgE1ms0mWbxsQA3qRkNMNCpxI3gDhXiBCCrCyGVQxgs3GWCYed4/Trf2nDmn+3Sfvvfz/Xz4MFPn1KmnquvUM11Vv3pEVTEMwzDKj4p8G2AYhmHkB3MAhmEYZYo5AMMwjDLFHIBhGEaZYg7AMAyjTKnMtwGpcMghh+jAgQPzbYZhGEZRsXLlyvdVtZc7vagcwMCBA1mxYkW+zTAMwygqROQdr3SbAjIMwyhTzAEYhmGUKeYADMMwyhRzAIZhGGWKOQDDMIwyJekuIBG5Gzgf2KaqJ0TTegAPAAOBBuArqvpR9Nos4JtAK/B9VX3C45m++Q3DMOL58aJVLFy+iVZVIiJMGXEY108amm+zSoIg3wB+C4x3pV0DPKWqQ4Cnor8jIscBk4Hjo3l+JSIRj2d65jcMw4jnx4tWce+yjbRGTy1uVeXeZRv58aJVebasNEjqAFR1KfChK/kCYH705/nApLj0+1V1n6puANYBp3k81i+/YRjGJyxcvimldCM10l0D6KOqWwGi//eOpvcD4j+ZzdG0oPk7ICJXisgKEVnR1NSUprmGYRQjrT7xSvzSjdTI9CKweKSF+qRUdZ6qDlfV4b16dVAyG4ZRwkTEa0jxTzdSI10H8J6IHAoQ/X9bNH0zcFjcff2BxhTyG4ZhfMKUEYellG6kRroO4BFgWvTnacAf49Ini0gnERkEDAFeTCG/YRjGJ1w/aShTRw745C/+iAhTRw6wXUAZQpLFBBaRhcBZwCHAe8C1wCLgQWAAsBH4sqp+GL1/NvAN4ADwA1X9SzT9TuA3qrpCRHr65U/E8OHD1Q6DMwzDSA0RWamqwzukF1NQeHMAhmEYqePnAEwJbBiGUaYUVTwAw0iFRS9vYe4Tb9C4vZm+dTXMOO9oJp3stSvZyCaX3vECz7396Qzv6ME9uO+KUXm0KPtksu9lsx/bNwCjJFn08hZmPbyKLdubUWDL9mZmPbyKRS9vybdpZYV78Ad47u0PufSOF/JkUfbJZN/Ldj82B2CUJHOfeIPmltZ2ac0trcx94o08WVSeuAf/ZOmlQCb7Xrb7sTkAoyRp3N6cUrphZIpM9r1s92NzAEZJ0reuJqV0w8gUmex72e7H5gCMkmTGeUdTU9X+INqaqggzzjs6TxaVJ6MH90gpvRTIZN/Ldj82B2CUJJNO7sdNFw2lX10NAvSrq+Gmi4baLqAcc98VozoM9qW+CyiTfS/b/diEYIZhGCWOCcEMwzCMdpgDMAzDKFNMCWwYAQirxgybP9dxcePtrRBojZspHtK7C4unnxX4WeNufZq3tn2cdv6gbed3X3zbiUBNZQXNLW1ZVejGXzu4pgoR2L6nJS99JxG2BmAYSYipMeMFOTVVkcCLcWHzx+LiusnWsche9roJOoi7B/9U8wdtO7/7ThlwcELRWSqfQ1C7gITtl8u+E8PWAAwjTcKqMcPmz3VcXC973XgN6qncFzR/0Lbzuy+Z4jgbCt1k7ZfLvpMMmwIyjCSEVWOGzZ/ruLiFpJYO2nZhbM6HQjdXfScZ9g3AMJIQVo0ZNn+u4+IWklo6aNuFsTnTCt0gz8tV30lGKAcgIleJyGoR+YeI/CCa9oCIvBL91yAir/jkbRCRVdH7bGLfKFjCqjHD5s91XFwve90M6d0l0LP87guaP2jb+d2XTHGcDYVusvbLZd9JRtpTQCJyAnAFcBqwH3hcRB5V1Uvi7rkF2JHgMWer6vvp2mAYuSC22JbuToyw+WMLvbnaBeS2N8wuoMXTzwq1Cyho2yW6Lxu7gILYlYldQGH7TjLS3gUkIl8GzlPVb0V//3/APlWdE/1dcOL9fk5V3/LI3wAMT8UB2C4gwzCM1MnGLqDVwBgR6SkitcAEIP476ZnAe16DfxQFnhSRlSJyZQLDrxSRFSKyoqmpKYS5hmEYRjxpTwGp6hoR+RmwGNgNvAociLtlCrAwwSNGq2qjiPQGFovIWlVd6lHOPGAeON8A0rXXMAzDaE+obaCqehdwF4CI3Ahsjv5cCVwEnJogb2P0/20i8gectYQODsAoDfKtpA2bf8QNi3lv1/5Pfu/TtZrls8clfG783LMbrxMx3WrfkUd0p+GDZhq3N1NZAS1tifMnwh2asaoCDrTRzub4ulRXVrDvQJvnswTYUD8xcNknXvs4O/d9upe9W6cIr103vsN9fupZAeItiQi0KVRFhP1xixN+beL32fmV7f4cB17zaIdnNqRQ/0HXPIrXX67x6xGJ1gnClp+IUEpgEekdHcAHAE8Co1T1IxEZD8xS1bE++boAFaq6K/rzYuAnqvp4ovJsDaA4ybeSNmx+9wASo1unCC1teD53xTsfeqp344kfsPzUvkHzJ8IrLm88NVURvnRqPx5auSWpACxGUCfgHvxjuJ1AEPVxENxt4vfZxTuBRP3jBw+84ltWkEHYb/BPRqbKj5EtJfBDIvI68Cfgu6r6UTR9Mq7pHxHpKyKPRX/tAzwrIq8CLwKPJhv8jeIl30rasPm9BhCAnftafZ8bRKUbPyino+oNGlc3iBp24fJNKQ2+QQc1r8HfKz2I+jgI7rr6fXbx6dlU26b753Wu4leHnQI60yf9ax5pjTgLxajqemBYmLKN4iHfStpcxwdu3N6c8oufLVVvsZSfT/VxocaPzkX5pgQ2sk6+lbS5jg/ct64mZZVutlS9xVJ+PtXHhRo/OhflmwMwsk6+lbRh8/fpWu2Z3q1TxPe5QVS68SrVdFS9QePqBlHDThlxWFL1bzxB3UW3Tt7PdKcHUR8HwV1Xv88uPj2batt03Wqu4lebAzCyTti4pvnOv3z2uA4DSZ+u1bx23Xjf514/aShTRw7w/cvavVjpvj8iwujBPT55dlVF4vyJ8IrLW1VBO5uvnzS0XV06VfoPDansAnrtuvEdBnuvXUDuz6iuporutVUIHQepiDg2VEfat61Xm/h9dvG7gBL1D7+F1qALsBvqJ/o6ARGoraroUN9Mlp8MiwdgGIZR4lg8AMMwDKMd5gAMwzDKFAsIU0RkKzaon1CoQpy54L3RkxNrqyvaneoYm3P1i1cbb2/nKkdZ2qZ0ULnGqyD9Tp48ZvZj7I270DkirL1hQsJ2SSaA8ppHdZcDznyz10RpQ/3EDnU/olct65v2BN5WGd/GbsVr/KmZfmpQP6FTUOI/L3d7VUeEllb1rTskFpnF+kdQJWsqdWmonxj4lNEg5bv70IHW1oS2NNRPDPw+HjnrUQ64GlGg3Tvh7mOx3yMinn3J1gDKjEzFBnWTbJBMRp+u1Z4vyujBPfj7xh0ZEff40Tki1F88zLNd+nfvHCjsYPyL5DX455shvbsEDp8YBr/PMRGjB/cI1Xfi2z6sI4vhdgJeg7+7/HRVyDVVkaTvo9fgnykKQQls5IhsqRXDvMDgr7R87u0Pszr4A+xtVd92SWfQLLTBH4LHzg1LOoNv2L4Ttnwv0mmvdFXIQd7HbA3+mcIcQJFQqGrFfFPu9TfCk8k+VGz90RxAkVCoasV8U+71N8KTyT5UbP3RHECRkC21YlA1qR9+SsvRg3tkRNmZiM4R8W2XoDFn3c8rNNKpRzr4fY6JCNt3wpbvRTrtla4KOcj7WFl4Xaod5gCKhLBqVj+8VKIxKgRqokrFfnU1HV6u0YN7sHz2uA4K1qkjB3DfFaPa2VtTVUFF9GVwq1zjVZDuMXhI7y401E/sMDjHdgH5tcvi6WclHaDci2hrb5jg6QT83uGG+okd6j6kd5eUztWJb2P3yxhb0EykBg07cMY+r+Wzx3Vor+qIJKx7or4DTv8IqmT1UuwmoqF+Yof+6LULKEj5Xn0omS0N9RMDvY/rbpro6QTc74T7ltjvfn3JdgEZhmEYgbBdQIZhGEY7zAEYhmGUKaGUwCJyFXAFzpTVHap6m4j8ezStKXrbv6rqYx55xwO3AxHgTlWtD2NLOeCnfEw3Lm2M+Nik8epEtxJ4S8AtbrH5+WyKYIzMEptpDvpx9aurSSvwTTxuRXgqz/JTZ8fsShTTONkzgtBQPzGhiLJP12oqI5HQbZSo/EyQ9hqAiJwA3I8TzH0/8Djwf4BLgd2qenOCvBHgTWAcTiD5l4Apqvp6ojLLeQ3APfjH6NO1mp17W9OOS2sYRnGSCSVwmG8AxwLLVHVPtIAlwIUB854GrIuGhkRE7gcuABI6gHLGT+HopaCMKRLf3bE322YZhlHEhFkDWA2MEZGeIlKLE+83FtboeyLymojcLSLdPfL2A+KjYG+OpnVARK4UkRUisqKpqcnrFsODxu3NeY/zahhGYZO2A1DVNcDPgMU40z+vAgeAXwODgZOArcAtHtm9Nrd6jlaqOk9Vh6vq8F69eqVrbtmRTlxawzDKi1C7gFT1LlU9RVXHAB8Cb6nqe6raqqptwB040z1uNvPptwWA/kBjGFtKHT+FY5+u1aHi0hqGUb6EcgAi0jv6/wDgImChiBwad8uFOFNFbl4ChojIIBGpBiYDj4SxpdRZPP0sT+Xj8tnj0o5LGyM+Nmm8OtGtBA5K54jQUO+tgDQKEyG1AOax/hYGtyI8FfzuDxLTONkzgtBQPzGhCrpP1+qMtFGi8jNBKCWwiDwD9ARagOmq+pSI3IMz/aNAA/BtVd0qIn1xtntOiOadANyGsw30blW9IVl55bwLyDAMI12ysQsIVT3TI+0yn3sbcRaKY78/BnTQBxiGYRi5wZTAhmEYZYrFBM4C8crcutoqVGFHc0s7lW4i9e6J1z7Ozn3tow2FUS0aRqYJqwT2msNOFL7Rjd/7EIuhm+33JdnzM1n+qHde5fCPtvI/J46jtcLZ8FEQawC5phjWAJLFF62pivClU/vx0Motnurdf1u0qsPgbxilSPwglsrgX+oc+f5GfvTMvXz+zefbpY+58g42dv90j02+lcCGB8niiza3tHqezRNT79rgbxjlxSEff8R3X3iQr6/8k+f1t3v056ef+2a7wT9TmAPIMEFigvopdIstnqhhGKnTuWUvX1v5Z2YsXUBEOx5Yt7u6hjljLuf+YePZX1mVVVvMAWSYIKdmxuYp08lrGEZxUdHWyhfWLGXmkgX02+V9nM2vRl7Mf532JXbUdM2pbeYAMsyM845Oew1gxnlH2xqAYZQAIze+xswl8zml8Q3P6w8ffza3jf5qVqZ1UsEcQIaJ7eRJtgto+OE9PHcBTTq5n+0CMgqeTO8CaqifWNS7gAZ/sIkfLb2HCa6F2xjPDziRuWMu5+V+x2SkfNsFZBiGkS+2bYMbb4Tbb/e+PmQI3HQTXHSRc9ZKnrFdQIZhGOnS3Ay//CXMmgWtHlO0tbXOgP/tb0OnTrm3L03MAWSIeGFXbXWEPftbbcrGMIoU0Ta+sOYZZi6ZT/+d2zzv+c1pF/GbkRezvaabk9AIXPvXnNiXqSkgcwAZwC3++ni/LeIaRrFx2qbVzFwyn+Fb1nheX3TcWH5+xqW8071vji3ryMBrHs2IEzAHkAGSib8Mwyg8jvhgM9OfvY/z1z7jeX35YScwZ8zlrOx/XI4tyx3mADKACbgMo/DpsWcH33nhQb614o+e1xvqDmXO2Gn85ejTUSmPczLNAWQAE3AZRuHRqWUfl738KDOXLKC67UCH6/siVcwZO417T57AvsrqPFiYf0I5ABG5CrgCZ1vsHap6m4jMBb4A7AfeBr6uqts98jYAu4BW4IDXFqViIZn4yzCM7CPaxsS1zzJzyXwG7HjP8555n72QX4+8mI9qD86xdYVJ2g5ARE7AGfxPwxnsHxeRR3GCxM9S1QMi8jNgFvAvPo85W1XfT9eGQsEt/rJdQIaRG4Zv/gczl8zntM2ve15/5Ngx/PyMS9nQo1+OLcsuhbAL6FhgmaruARCRJcCFqjon7p5lwMUhyigaYipewzCyyFtvwb/9G9x/v/f1M85wBFpnOsEKvxj9Z3gTZqVjNTBGRHqKSC1OuMfDXPd8A/iLT34FnhSRlSJypV8hInKliKwQkRVNTd4HKRmGUaK8/z5cfbWjphWBo45qP/gPGuT83toKqvDMM58M/kZy0v4GoKprolM8i4HdwKvAJystIjI7+vt9Po8YraqNItIbWCwia1V1qUc584B54BwFka69hmEUAXv3wq9/Df/6r87PbqqqHMXtd74DNTW5t6/ECBsU/i7gLgARuRHYHP15GnA+cI76HDYUDRKPqm4TkT/grCV0cACFyqV3vMBzb3+YbzMMo6gRbePzbzzPzCXzGbh9q+c9dw6/gF+N+gofxhZum4Dr/jd3RhYghbAGgIj0jg7gA4CLgFEiMh5n0XdsbH3AI18XoEJVd0V//ifgJ2FsySU2+BtG+py6+XVmLl3AiE2rPa//+egz+PmZl/J2T/eMshGjUJTAD4lIT6AF+K6qfiQivwQ64UzrgLNQ/M8i0he4U1UnAH2AP0SvVwK/U9XHQ9qSM2zwN4zgHP5RIz989j4mvb7E8/qKfscyd8zlLB8wNMeWGWGngDqstqjqkT73NuIsFKOq64FhYco2DKMwqWveyT8v+z3//OLDntc3d+vFnLHT+NOxY8pGcVuomBLYMIxQVB9o4dJXHmPG0gXUtuzrcP2AVDBn7DQWnDKRvVWd82Ch4Yc5gDQYPbiHTQMZ5Ysq4990Fm6P+KjR85a7T/0i/znqK3zQpS63thkpYQ4gDe67YpQtBBtlxSlb1jBj6QJGbVzlef2xo07nljMv4+1DbOE2FxTELqBy5r4rRuXbBMPIHuvXw7XXwr33el8fOdJR3J59NuAs7k3InXVGhjAHYBgGfPQR/Oxnzj8v+vd3BFhTpkAkklvbjKxhDsAwypF9+2DePEdxu3t3x+sizoD/ve9Bly65t8/ICeYAosTH9K2rrUIVdjS3UFkBLW35ts4wQqLKeW+9wMwlCxj84WbPW357yvn856hLaDqou5PwEfDTp3NlYUo01E/kyFmPciBPh8M01E/kmNmPsbfV24DOEfG9FssfP+akWo1MrQGIz0kNBcnw4cN1xYoVGX+uO6avYZQCJzW+wYyl8xn9zmue1x8/ahS3nDGVt3odnmPLDICaqkioMScVJyAiK71irtg3ACymr1Ea9N/+Lj987nd8abX3OTmvHHoUc8ZczvMDT8qtYYYnhTDmmAPAYvoaxUm3vbv59vKH+O6y//G8/u5BPZgzdhqLjjuLtgpbuDU6Yg4Ai+lrFAdVrS1c8uqTzFwyn277Pc9ZZM6Yy/nvU79Ic7Upbo3kmAPAYvoaBYoq49YtZ+aS+Qz5YJPnLQtOnsgvR32FbV175tg4Iyxh1wAygTkAOsb0tV1ARr4YuvUtZixdwJiGlz2vLz5yBDePuYw3eg3MrWEFhu0Csl1AhlH8vPMO/Pu/w29/63391FOd/fjnnuvszTeMNLBdQIZRCOzYAXPnwg03eF//zGecIxYuuwwq7fU0sov1MMPIJi0tcNddMGsWbN/ufc9Pfwo/+AEcdFAuLTOM0CEhrwKuAAS4Q1VvE5EewAPAQKAB+IqqfuSRdzxwOxDBiRRWH8aWTGInfRppo8o5b7/IzCXzOfr9jZ633HvS5/mP0y/hva6HOAm7geu9o2UVKv3qatKau84mAmyIzo1n+x1uqJ/IjxetYuHyTbRGp9EFUCAiwsgjutPwQXPCNhKgtjrCnv2txbcGICInAPfjBHPfDzwO/B8ch/ChqtaLyDVAd1X9F1feCPAmMA4nkPxLwBRVfT1RmblYA7DB30iV499dx8ylCxi74e+e1/86+LPcMuYy1vQ+IseWlR8CnF4m8TryrQQ+Fife755oAUuAC4ELgLOi98wHnsYJEh/PacC6aGhIROT+aL6EDiAXlEPHMcLRd+c2rnp2IZesWux5fXWfwcwZczlLB51iC7c5RrF3OBXCOIDVwA3RoPDNOMeBrwD6qOpWAFXdKiK9PfL2A+I3Nm8GRngVIiJXAlcCDBgwIIS5hpEeXfd9zLdeXMRVzy/0vN5UW8fcMZfz0NBzaDXFrVFEpO0AVHWNiPwMWIwzi/kqcCBgdq8/izznolR1HjAPnCmgNEw1jJSobD3Al1f9lZlL5tN97y7Pe24941LuGn4BH3eqzbF1hpE5Qi0Cq+pdwF0AInIjzl/y74nIodG//g8Ftnlk3QzEx47rD3gHF80xFu+3DFHl7PUrmLlkPsc2NXje8rth4/nF6ZN5t9shubXNSIlyWgPIBGF3AfVW1W0iMgC4CBgFDAKmAfXR///okfUlYIiIDAK2AJOBr4axJVNYvN/y4Pj33ubqpQs4e/1Kz+v/e8RwbhlzGf/oMzjHlhUHtguozHcBAYjIM0BPoAWYrqpPRdcEHgQGABuBL6vqhyLSF2e754Ro3gnAbTjbQO9WVR9lzKeYEthIm02b4Cc/gTvv9L4+bJijuB0/3hZujZIjK0pgVT3TI+0D4ByP9Ebi4kar6mPAY2HKNwxfdu6En//cOWbBi0MOcRS3X/saVFXl0jLDKBhMCWyUBgcOOOfpzJoF77/vfc+118L06dCtW05NM4xCxRxAFJv3LzJUOWv9SmYsXcDx29Z73rLwxH/iP0ZPprFbdCfyXuDGZ3JnYwkTEflk7jsMlUJaJ3o21E/s8M66T+CswJmTT/T40YN7eK77xebz/RCgpqqC5gNtxJohfg1gyojDuH7SUAAGXvOo7zNiZVQIdKqsYG9LW6D1gIJYA8g12VoDsMG/ODh223quXnoP57z9kuf1pwedys1jLmP1Z47MsWVGMdOtU4Sd+zJ/Lv/UkQO4d5n3cSCZIN9K4JLBBv/CpM+u97nqufv56quPe15f02sgc8ZO429HDLeFWyNtsjH4Ayxc7h3Ep5AwB2AUDF327eEbK/7Ij569z/P69s4HMWfsNB4cOo4DEeu6RmGTiSmybGNvkZE3Im2tXLT6KWYuWUCvPds977n99MncedqF7OrUJbfGGUZIMrVOkk3MAWDq35yhypgNf2fG0gUMfe9tz1seGDqOX4yewpaDvY6QMozMk601gCkjDsvqGkAmsEXgKLYQnB2Obmrg6qULGLfuRc/rSweezNwxl7Pq0CE5tswIg+0CKq5dQH6LwOYAjMzS2OhEuPrNb7yvH3+8o7g9/3xbuDWMHGG7gIzssHs33H47/PjH3tcPPtgZ8L/5Taiuzq1thmEkxByAkRqtrXDPPY7i9t13ve+ZPRuuvhrq6nJqmmEYqVHWDmDEDYt5b9f+fJtR8IxueIWZS+Yz7N23PK///oRzuO2Mr7L54D5OwgGg/rncGWjknNgctNf8dkP9xKTvViz/uFuf5q1tH6dV/qKXtzD3iTdo3N5M37oaBvasYdn6jwKvTcTPwbvn7d0nfXrlFYE2j8sREY7oVcv6pj1JbYnZkGzNwY0pgUNig78/RzU1cPUz9/JPby3zvP7s4cOYO+ZyXu17dI4tM0qJIb27pDX4x6ipitDcktndO1NHOlEHC333DpgSOBQ2+H9Kr90f8n+ff4DLX/berbCuR3/mjJ3Gk0NG2sKtkTHCDP5Axgd/KA71biYpWwdQztTs38vXVz7CzKULPK/vqq5hzthpPHDieeyvtKOSjfKh0IVbmcYcQBlQ0dbKpNefZuaS+Xxmt7fW4VcjL+Y3Iy5mZ+eDcmydYRQOkeg33HJxBGFDQv4Q+BbO+sUq4OvAfCA2OVwHbFfVkzzyNgC7gFbggNf8VDbp07W6pKeBTm94hZlLF3DS1jc9rz90/NncdsalbKr7TI4tMwyHQlwDmDLCCVVeDGsAmSBtByAi/YDvA8eparOIPAhMVtVL4u65BdiR4DFnq6pP9I7ssnz2uJJaCD7y/Y1c/cw9jH/zBc/rzw84kbljLuflfsfk2DKjFCn1XUCA7QJKmNFxAMuAYcBOYBHwC1V9MnpdcGICf05VO+wfjH4DGJ6KAzAlcBy7d8N118HNN3tfP+ooR4B14YW2cGsYZU7GdwGp6hYRuRlnkG8GnowN/lHOBN7zGvxjjwCeFBEF/ktV5/kYfiVwJcCAAQPSNbf4aWmB5cvhqafgr3+FZcucMIgxamudAf/b34ZOnfJnp2EYRUOYKaDuwAXAIGA78D8iMlVV743eMgVYmOARo1W1UUR6A4tFZK2qLnXfFHUM88D5BpCuvUVHWxusXu0M9k89BUuWwMcfO3/Nn3oq/OhHcOyxzpk6PXvm21rDMIqQMIvA5wIbVLUJQEQeBk4H7hWRSuAi4FS/zKraGP1/m4j8ATgN6OAAMkmhn/jZf/u7jH7nVc5oeIVRG1/jkD3O8snbPfrx/FFjefbwk1g2YCg7aro6GdYAa7zFWoaRDAGqIsL+1tT/rorNQR8569EOp3l6nZTpRSpz5V7lu9cAzj6mF39b20Tj9mYqK6ClLfEzEs27D+ndhT3722jc3ux5j7v8+PpGRBh5RHcaPmhOmN+tNk7lNNFCWAMYAdwNfBZnCui3wApV/Q8RGQ/MUtWxPnm7ABWquiv682LgJ6rqHfsvSpg1gEIc/Hvs2cGod15j9DuvMPqdVzl8u3O2zrYu3Xl24Ek8f/gwnjt8GFu79cqzpYbRkXSPcs4U2dgFVEjlJ4spnFclsKouF5HfA3/HOf3lZaJTNcBkXNM/ItIXuFNVJwB9gD8468RUAr9LNviHpRAG/54fb+d7LzzAueteZFenWo7btgGAndW1LB8wlP8+9Ys8O/Ak1vU8zBZujYInn4M/ZEcJXEjl50KVHEoHoKrXAtd6pH/NI60RmBD9eT3O7qGSplPLPqb9/c/MXDKfSm3/ffSFAUOZe+ZlPH/4MF47dAitFZE8WWkYRiGSCzGaKYEziGgbX1izlJlL5tN/Z5PnPf912kX8euTFbK/plmPrDMMoJnIRU7hsHEC24v6O2LiKGUsXMHzLGs/rfzx2LD8/46s09OiX8bINI5/YGkB2y89FTOGyOg46EwvBR3ywmenP3Mv5bzzreX35YScwd8xlrOh/fKhyDCPb2C6g8tkFZDGB06WpCW68EW67zfv6EUc4AqyLL4aKipyaZhiGEQSLBxCU5mb41a+ckIctLR2vV1c7A/53vgOdO+fePsMwjAxhDqCtDR580BnwGxq875k+Ha65BnrZfnzDMEqHkncA8fNssTm2z25azcyl9/DZzf/wzPPnY87k1jMuZX3P/p8m3vJiTuw1ip9+dTW+c7+ZRIDa6gh79rd+UtYnp0sK1FRW0NzSRt+6GrZsb85o2bE5aPepn326VrN89rh29yaaw060LhdTwgSZQ3fPm8fPzwfJ7z4Z9JCDqgKdZupHfPl1tVWowo7mFg6uqUIEtu9poW9dDTPOO5pJJyfeIFKQSuB8kOoawI8XreLeZRupam3h1j/fyhfWPuN530v9jmPu2Mt58bATMmWqYZQ8fjE14p2A1+AVIxs786aOHMDww3sw6+FVWd8h5DcIL3p5S+Dya6oi3HTRUF8nkKj9LCZwEmJKusv//mi7wX/TwX2YO+Zy/nTsmajYwq1hpIPfX8hBY2xkY1v2wuWb+NvaprxuD537xBuBy29uaWXuE28k/RaQLUraAcS2V/1u2Hg2d+vN00ecyr4qOyrZMEqVVlUaMzzdlSqplp9Pe0v6z99YfM/m6s48cfTpNvgbRokTEaFvXU1ebUi1/HzaW9IOIBbf0zCMzNOna3VK6W5GD+6RSXMA552fcd7R1FTl72ytVMqvqYow47yjk9+YJUraAVw/aShTRw745JtA/PmaETtt08gS/epqyEXvEqBLdaRdWbGfRaC2qgKJ2pNpGuonsnz2uA6DvXsXkN9CZUP9RO67YlRCJyDg244N9RPbvdsREaaOHMD1k5wF1ZsuGprwc3Dnd48NyZxYogVYd/nda6uoq6lCgLqaKrrXVn3yuSRaAE5Uju0CMgzDMALhtwuopL8BGIZhGP6E2gUkIj8EvoWjoVgFfB24BrgCiJ2H/K+q+phH3vHA7UAEJ1BMfRhb/HAfuGQYmcJLqFQpoAQ/xjdezFVdWcG+A23triV6SkP9xEAHHPodK+w+0CxSIRxoS263ABt8hFyjB/fgvitGtbs/HSFTsvc2FSEWtG9HL7FaItwH3lUKrLup42F0fqKuIG3kZ3vfuhoOtLa221o7pHcXFk8/K7D9iQgTErIf8CxwnKo2i8iDwGPAQGC3qt6cIG8EeBMYB2wGXgKmqOrricpMVwhmGIY36R5pLMDpPkKu+AEuHSFT0Pc2jBArqBPwOu0UnPp3drWdl6jLz0H7OYGgIrJUnUC2poAqgZpoEPhaoDFgvtOAdaq6XlX3A/cDF4S0pQO5CKlmGMVMuoIpxV/IFVbgFfa9DSLECipW84t3oHRsu5ioK55U2yioiOytbR8nvScIaTsAVd0C3AxsBLYCO1T1yejl74nIayJyt4h098jeD4j/lDdH0zogIleKyAoRWdHU5B1lyw+b9jGM4iPse5tPYVXYsnNte9oOIDqwXwAMAvoCXURkKvBrYDBwEo5juMUru0ea56euqvNUdbiqDu+V4mmcttXTMIqPsO9tPoVVYcvOte1hpoDOBTaoapOqtgAPA6er6nuq2qqqbcAdONM9bjYD8Sqt/gSfPgqMCcEMIzHpCqYEfyFXWIFX2Pc2iBArqFit0scXOVHP2pfhJepKtY2CisiG9O6S9J4ghHEAG4GRIlIrIgKcA6wRkUPj7rkQWO2R9yVgiIgMEpFqYDLwSAhbPHELwQwjk3gJlSoltb9g48VcnSorOlxLREP9xECDrZ89DfUT2wmWKiuC2R3bBeQl5HIvbqYjZAry3qYixHI/JZVdQOtumtjBCVSKU//4MvxEXUHaKJHt/epqOjirgtgFBCAi1wGXAAeAl3G2hN6JM/2jQAPwbVXdKiJ9cbZ7TojmnQDchrMN9G5VvSFZeSYEMwzDSB2LCWwYhlGmmBLYMAzDaEdJxwOAjiHrjNLCT+WaC7yUuN06Rdi5L7W99bEp5soKaPlUCEzniLC31b9uXuXH5pfd4RL9lMB+JFLixiuB41Wr8eEp40M0hg1pOO7Wp9vte/ebA/dT5gbN7/esdMI4xpModGUQUlUSp0JJTwHZ4G+UI36hGr3wGoiDKHEF+PklJ4UKvRjECbgH7xjuQdxLQVtTFaFb54hnWyRyAsnUuMnCOMbj15axk0uTkaqS2I+ynAKywd8oR8L2+yBKXCW10Ifp4qd4dad72dLc0urbFomUtMnq5aX49cOvLYOqnbOlto5R0g7AMIzUCTqllu/Qi/Fk0pYgzwpanl9bFsopBeYADMNoR1AdQ75DL8aTSVuCPCtoeX5tWSjapJJ2AEHVfoZRSoTt90GUuEJqoQ/TxU/x6k73sqWmKuLbFomUtMnqlUoYR7+2DKp2zpbaOkZJOwCvkHVGaZHPv6S8lLjdOqU+IMbUqlWut7FzJHHdvMofPbgHy2eP6xAu0S+/F8mUuLFdQG7Vanx4yliIxrAhDRdPP6vDYO21gOuloL3poqEsnz0uUP5Ez0o1jGM87raMD10ZhFSVxKlS0ruADMMwjDLdBWQYhmH4Yw7AMAyjTCl5JXC8oq94JruMoEREaFPt8Nk6IfucGLt+YW4FqIoI++PUtn26VvP+7pZPtuklissbH8/XrX514xdXNijHzH6snSq4c0RYe8OEdvckUq9u8di2GHQePt9K1vjyK8Q5NXVvS1tgVW7Q2L2FStj2T0RJrwEEja9pGJnEvcjnF1c2qBNwD/4x4p1Aun09SHD2fCpZk6mSk6ly/RTCqSzk5pOw7R+jLNcAcqFUNAw3bpWnX1xZv3Q3fucBxadnq6/nW8marJxkqlw/hXBQJW++Cdv+yShpB1BISkWjfMiHyjNbfT3fStYg5SSqu9+1Yhkbst3+Je0ACkmpaJQP+dAmZKuv51vJGqScRHX3u1YsY0O22z+UAxCRH4rIP0RktYgsFJHOIjJXRNaKyGsi8gcRqfPJ2yAiq0TkFRHJyub+XCgVDcONW+XpF1fWL92NnyAsPj1bfT3fStZk5SRT5fophIMqefNN2PZPRtoOQET6Ad8HhqvqCTihHScDi4ETVPVE4E1gVoLHnK2qJ3ktTmQCt6LPKD0iIp6frRO0u4JEYW4FqHYNrn26Vrf76ypRv/FTv7oX5/ziygbdBbT2hgkdnIB7F1Ay9aoXQXYB5VvJ6i6/QpzPNagq108hXAwLwBC+/ZOR9i6gqANYBgwDdgKLgF+o6pNx91wIXKyql3rkb8BxHu8HLdOUwIZhGKmT8V1AqroFuBnYCGwFdsQP/lG+AfzF7xHAkyKyUkSu9CtHRK4UkRUisqKpqSldcw3DMAwXYaaAugMXAIOAvkAXEZkad302cAC4z+cRo1X1FODzwHdFZIzXTao6T1WHq+rwXr16pWuuYRiG4SKMEvhcYIOqNgGIyMPA6cC9IjINOB84R33mmFS1Mfr/NhH5A3AasDSEPZ7EqwCrKx1lqFE6OGsA2mFPvUA7NaxXJxSgrrYKVdjR7K+Y9VMDJ5tDT6RC79O1muWzxyXM7/eseDVrUJXridc+3i5WcbdOEV67bnzK5aVjY9iYvEHV1kbqhFkDGAHcDXwWaAZ+C6wA3gJuBcbGnINH3i5Aharuiv68GPiJqj6eqExTAhuFhp8TCNL3gjoBPzXrl07tx0MrtyRVuboH/xh+TiAd9WwuY/JC6krYcicbawDLgd8DfwdWRZ81D/gl0BVYHN3i+ZuoAX1F5LFo9j7AsyLyKvAi8GiywT8dTAls5IsgfS9o7F4/NevC5ZsCqVy9Bv9E6emoZ3MZkxcyp4Qtd0IdBqeq1wLXupKP9Lm3EZgQ/Xk9zu6hrFIsaj+j9MhFjFo/NWjYstNRz+Y6Jm+hxNQtdkwJbBhZIBcxav3UoGHLTkc9m+uYvIUSU7fYKWkHYEpgI18E6XtBw5X6qVmnjDgskMrVL0ylX3o66tlcxuSFzClhy52SdgBuFWCnypKublkSEfE8UsGthvVCgO61VdTVJFbM+uVPtAsomQo9lV1AfmrW6ycNDaRyfe268R0G+0S7gNJRz2YzJm8QtbWRHiUdD8AwDMMo03gAhmEYhj/mAAzDMMqUko8JHI9bkditU4SP97fZlrIQeKlkYydVphuPuaoCDrTRTk2aKC6qX8xYd7zfePzmof3KCRqXNaxi14+wz81WXNwgz41vOxGoqaygOYWYvrmwsZDzZ5OyWQNwD/5GdqkUqKqMhBbi1VRFOGXAwZ4hBKeOHACQMGZsItxOwC/+6pDeXTz7jnsxMqxi14+wz81WXNwgzw0b0zcsYeue7/yZouzXAGzwzy0HlIyosJtbWn3jxy5cvimUItTdJ/ye5dd33PeHVez6Efa52YqLG+S5YWP6hiVs3fOdP9uU1RSQUVpkeuou1ee578+WYjfsc7MVFzfIc8PG9A1L2LrnO3+2KZtvAEbpERHJqCI01We578+WYjfsc7MVFzfIc8PG9A1L2LrnO3+2KRsHkEh5aGSeSiEjKuyaqohv/NgpIw4LpQh19wm/Z/n1Hff9YRW7foR9brbi4gZ5btiYvmEJW/d85882ZeMAFk8/q8OL3K1TxM4UCYlX63WOCOtumph2POaqCtqpSe+7YpRvXNREMWPd8X7j8doF5Bd/dfH0swLFZQ2r2PUj7HOzFRc3yHPdbSoCtSnE9A1L2LrnO3+2KZtdQIZhGOVK2e8CMgzDMNpjDsAwDKNMCbUNVER+CHwLRwy6Cvg6UAs8AAwEGoCvqOpHHnnHA7cDEeBOVa0PY0sQ3GrOQw6qChyVqVDxi1ebSv74uLipPKtSYN1NEwOpZN1qyF3N+9tFpIqdjun3rGNmP8beOFVvTG3s9WwvlWxNVQXNB9pQzU9c2UJWg3pRbPYa6REmJnA/4FngOFVtFpEHgceA44APVbVeRK4Buqvqv7jyRoA3gXHAZuAlYIqqvp6ozDBrAMkUiUZmiV8kDRqbuXNE2g3yMfycXOeIUH/xsMAq2UQ2ZpNCUYMGpdjsNZKTrTWASqBGRCpx/vJvBC4A5kevzwcmeeQ7DVinqutVdT9wfzRf1rAYorklvr2Dxmb2GvzB/xvO3lZNSSWbyMZsUuhqUDfFZq+RPmGCwm8BbgY2AluBHar6JNBHVbdG79kK9PbI3g+If/s2R9M6ICJXisgKEVnR1NSUrrl24FuOiW/vfCg9g3zeueoTha4GdVNs9hrpk7YDEJHuOH+1DwL6Al1EZGrQ7B5pnm+jqs5T1eGqOrxXr17pGYvFEM018e2dD6VnkM87V32i0NWgborNXiN9wkwBnQtsUNUmVW0BHgZOB94TkUMBov9v88i7GYiXCPbHmT7KGhZDNLfEt3fQ2MydfYRbfsN054ikpJJNZGM2KXQ1qJtis9dInzAOYCMwUkRqRUSAc4A1wCPAtOg904A/euR9CRgiIoNEpBqYHM2XNbxUnkGDchcyYf+GdcfFTYVKceLiJlPJeqkh3TFq+3StZu0NEzyftaF+YgfnENsFFFQlW1tVQewP/lzHlS10NaibYrPXSJ9QSmARuQ64BDgAvIyzJfQg4EFgAI6T+LKqfigifXG2e06I5p0A3IazDfRuVb0hWXmmBDYMw0gdv11AdhSEYRhGiWNHQRiGYRjtMAdgGIZRppgDMAzDKFPMARiGYZQpRbUILCJNwDvAIcD7eTYnn5Rz/cu57lDe9S/nukO4+h+uqh2UtEXlAGKIyAqvFe1yoZzrX851h/KufznXHbJTf5sCMgzDKFPMARiGYZQpxeoA5uXbgDxTzvUv57pDede/nOsOWah/Ua4BGIZhGOEp1m8AhmEYRkjMARiGYZQpRecARGS8iLwhIuuiMYdLFhE5TET+JiJrROQfInJVNL2HiCwWkbei/3fPt63ZQkQiIvKyiPw5+ns51b1ORH4vImujfWBUudRfRH4Y7fOrRWShiHQu5bqLyN0isk1EVsel+dZXRGZFx8A3ROS8dMstKgcQDSb/n8DncYLPTxGR4/JrVVY5APxIVY8FRgLfjdb3GuApVR0CPBX9vVS5CifORIxyqvvtwOOqegwwDKcdSr7+ItIP+D4wXFVPwDkyfjKlXfffAuNdaZ71jY4Bk4Hjo3l+FR0bU6aoHAB5CCafT1R1q6r+PfrzLpwBoB9OnedHb5sPTMqLgVlGRPoDE4E745LLpe7dgDHAXQCqul9Vt1Mm9QcqgRoRqQRqcSIGlmzdVXUp8KEr2a++FwD3q+o+Vd0ArMMZG1Om2BxA4GDypYaIDAROBpYDfVR1KzhOAuidR9OyyW3ATKAtLq1c6n4E0AT8d3QK7E4R6UIZ1F9VtwA34wSU2grsUNUnKYO6u/Crb8bGwWJzAIGDyZcSInIQ8BDwA1XdmW97coGInA9sU9WV+bYlT1QCpwC/VtWTgY8prSkPX6Jz3RcAg4C+QBcRmZpfqwqKjI2DxeYAch5MPt+ISBXO4H+fqj4cTX5PRA6NXj8U2JYv+7LIaOCLItKAM9X3ORG5l/KoOzh9fbOqLo/+/nsch1AO9T8X2KCqTaraAjwMnE551D0ev/pmbBwsNgeQ82Dy+UREBGcOeI2q3hp36RFgWvTnacAfc21btlHVWaraX1UH4nzO/6uqUymDugOo6rvAJhE5Opp0DvA65VH/jcBIEamNvgPn4Kx/lUPd4/Gr7yPAZBHpJCKDgCHAi2mVoKpF9Q+YALwJvA3Mzrc9Wa7rGThf7V4DXon+mwD0xNkV8Fb0/x75tjXL7XAW8Ofoz2VTd+AkYEX0818EdC+X+gPXAWuB1cA9QKdSrjuwEGe9owXnL/xvJqovMDs6Br4BfD7dcu0oCMMwjDKl2KaADMMwjAxhDsAwDKNMMQdgGIZRppgDMAzDKFPMARiGYZQp5gAMwzDKFHMAhmEYZcr/B46UvAnd6NOTAAAAAElFTkSuQmCC
"
>
</div>

</div>

</div>

</div>

</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>This seems to match our data somewhat better, however are there other approaches we can utilize.</p>

</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[16]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">from</span> <span class="nn">sklearn.linear_model</span> <span class="kn">import</span> <span class="n">SGDRegressor</span>
<span class="kn">from</span> <span class="nn">sklearn.datasets</span> <span class="kn">import</span> <span class="n">load_boston</span>
<span class="kn">from</span> <span class="nn">sklearn.datasets</span> <span class="kn">import</span> <span class="n">make_regression</span>
<span class="kn">from</span> <span class="nn">sklearn.metrics</span> <span class="kn">import</span> <span class="n">mean_squared_error</span>
<span class="kn">from</span> <span class="nn">sklearn.model_selection</span> <span class="kn">import</span> <span class="n">train_test_split</span>
<span class="kn">from</span> <span class="nn">sklearn.model_selection</span> <span class="kn">import</span> <span class="n">cross_val_score</span>
<span class="kn">from</span> <span class="nn">sklearn.preprocessing</span> <span class="kn">import</span> <span class="n">scale</span>
</pre></div>

     </div>
</div>
</div>
</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[23]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">xtrain</span><span class="p">,</span> <span class="n">xtest</span><span class="p">,</span> <span class="n">ytrain</span><span class="p">,</span> <span class="n">ytest</span><span class="o">=</span><span class="n">train_test_split</span><span class="p">(</span><span class="n">x</span><span class="p">,</span> <span class="n">y</span><span class="p">,</span> <span class="n">test_size</span><span class="o">=</span><span class="mf">0.25</span><span class="p">)</span>
<span class="n">sgdr</span> <span class="o">=</span> <span class="n">SGDRegressor</span><span class="p">()</span>

<span class="n">sgdr</span><span class="o">.</span><span class="n">fit</span><span class="p">(</span><span class="n">xtrain</span><span class="p">,</span> <span class="n">ytrain</span><span class="p">)</span>

<span class="n">score</span> <span class="o">=</span> <span class="n">sgdr</span><span class="o">.</span><span class="n">score</span><span class="p">(</span><span class="n">xtrain</span><span class="p">,</span> <span class="n">ytrain</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;R-squared:&quot;</span><span class="p">,</span> <span class="n">score</span><span class="p">)</span>

<span class="n">cv_score</span> <span class="o">=</span> <span class="n">cross_val_score</span><span class="p">(</span><span class="n">sgdr</span><span class="p">,</span> <span class="n">x</span><span class="p">,</span> <span class="n">y</span><span class="p">,</span> <span class="n">cv</span> <span class="o">=</span> <span class="mi">10</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;CV mean score: &quot;</span><span class="p">,</span> <span class="n">cv_score</span><span class="o">.</span><span class="n">mean</span><span class="p">())</span>

<span class="n">ypred</span> <span class="o">=</span> <span class="n">sgdr</span><span class="o">.</span><span class="n">predict</span><span class="p">(</span><span class="n">xtest</span><span class="p">)</span>

<span class="n">mse</span> <span class="o">=</span> <span class="n">mean_squared_error</span><span class="p">(</span><span class="n">ytest</span><span class="p">,</span> <span class="n">ypred</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;MSE: &quot;</span><span class="p">,</span> <span class="n">mse</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;RMSE: &quot;</span><span class="p">,</span> <span class="n">mse</span><span class="o">**</span><span class="p">(</span><span class="mi">1</span><span class="o">/</span><span class="mf">2.0</span><span class="p">))</span> 

<span class="n">x_ax</span> <span class="o">=</span> <span class="nb">range</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">ytest</span><span class="p">))</span>
<span class="n">plt</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">x_ax</span><span class="p">,</span> <span class="n">ytest</span><span class="p">,</span> <span class="n">linewidth</span><span class="o">=</span><span class="mi">2</span><span class="p">,</span> <span class="n">label</span><span class="o">=</span><span class="s2">&quot;original&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">x_ax</span><span class="p">,</span> <span class="n">ypred</span><span class="p">,</span> <span class="n">linewidth</span><span class="o">=</span><span class="mf">2.1</span><span class="p">,</span> <span class="n">label</span><span class="o">=</span><span class="s2">&quot;predicted&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">title</span><span class="p">(</span><span class="s2">&quot;Y-test and Y-predicted data for SGD Regressor&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">xlabel</span><span class="p">(</span><span class="s1">&#39;X-axis&#39;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">ylabel</span><span class="p">(</span><span class="s1">&#39;Y-axis&#39;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">legend</span><span class="p">(</span><span class="n">loc</span><span class="o">=</span><span class="s1">&#39;best&#39;</span><span class="p">,</span><span class="n">fancybox</span><span class="o">=</span><span class="kc">True</span><span class="p">,</span> <span class="n">shadow</span><span class="o">=</span><span class="kc">True</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">grid</span><span class="p">(</span><span class="kc">True</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span> 
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>


<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="text/plain">
<pre>CV mean score:  -64.99471316517506
MSE:  8.387096044012836
RMSE:  2.8960483497367298
</pre>
</div>
</div>

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedImage jp-OutputArea-output ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>

</div>

</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>Above we use SGDRegressor() to implement a plain stochastic gradient descent (SGD) learning routine. This routine utilizes different loss functions and penalties in order to fit linear regression models for the training data above. With the large Root and MSE value we can see this is not a perfect regression model. The pearson-correlation values we looked at prior to implementing this makes these graphs make sense. We can see this as price may not be the greatest indicator of points after a certain price. It appears that the point system</p>

</div>
</div>
</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><strong>Communication of insights attained</strong></p>

</div>
</div>
</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>Contrary to popular belief there are many bottles that are great and relatively cheap An example search with results is shown below.</p>

</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[&nbsp;]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">less_than_15_dollars</span> <span class="o">=</span> <span class="n">wine_data</span><span class="p">[</span><span class="n">wine_data</span><span class="p">[</span><span class="s2">&quot;price&quot;</span><span class="p">]</span> <span class="o">&lt;=</span> <span class="mi">20</span><span class="p">]</span>
<span class="n">cheap_excellent</span> <span class="o">=</span> <span class="n">less_than_15_dollars</span><span class="p">[</span><span class="n">less_than_15_dollars</span><span class="p">[</span><span class="s2">&quot;points&quot;</span><span class="p">]</span> <span class="o">&gt;=</span> <span class="mi">95</span><span class="p">]</span>
<span class="n">cheap_excellent</span><span class="o">.</span><span class="n">head</span><span class="p">(</span><span class="mi">5</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[&nbsp;]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">one_hundred_points</span> <span class="o">=</span> <span class="n">wine_data</span><span class="p">[</span><span class="n">wine_data</span><span class="p">[</span><span class="s2">&quot;points&quot;</span><span class="p">]</span> <span class="o">==</span> <span class="mi">99</span><span class="p">]</span>
<span class="n">one_hundred_points</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
</pre></div>

     </div>
</div>
</div>
</div>

</div>
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>I intend on exploring some of the options above. However, one note is that with such a p-value it may seem like a done deal to not think that expensive bottles of wine may be worth it, but that is not the goal of this process. The process is meant to uncover the hidden gems that are not explored and to understand wine does not have to be elitist. Be safe, enjoy responsibly, and thank you for a great semester!
Visit local winery. For Maryland the link is provided below. This project was very insightful in seeing the value of that 20-25 bottle of wine. In that range, there appears to be a ton of value and the bottles listed above are just a small example of that.</p>
<p><a href="https://marylandwine.com/map/">Interactive Wine Map of Maryland</a></p>

</div>
</div>
</div>
</body>







</html>
