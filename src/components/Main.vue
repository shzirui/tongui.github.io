<template>

  <head>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css">
    <!-- <meta charset="UTF-8"> -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
  </head>
  <div class="main">
    <div class="section header">
      <div class="title"><img class="mat-icon" src="/icon2.png">TongUI</div>
      <div class="subtitle">
        TongUI: Building Generalized GUI Agents by Learning <br>from Multimodal Web Tutorials
        <!-- TongUI: Building Generalized GUI Agents by Learning \\ from Multimodal Web Tutorials -->
      </div>


      <div class="author-list">
        <!-- &#9733 &#9993;-->
        <span class="author">
          <el-link href="https://bofei5675.github.io/">Bofei Zhang</el-link>
          <span class="ind">1&#9733;</span>,
        </span>
        <span class="author">
          <el-link href="">Zirui Shang</el-link>
          <span class="ind">2,1&#9733;</span>,
        </span>
        <span class="author">
          <el-link href="https://zhigao2017.github.io/">Zhi Gao</el-link>
          <span class="ind">1,3&#9733;</span>,
        </span>
        <span class="author">
          <el-link href="">Wang Zhang</el-link>
          <span class="ind">1</span>,
        </span>
        <span class="author">
          <el-link href="">Rui Xie</el-link>
          <span class="ind">1,4</span>,
        </span>
        <br>
        <span class="author">
          <el-link href="https://jeasinema.github.io/">Xiaojian Ma</el-link>
          <span class="ind">1</span>,
        </span>
        <span class="author">
          <el-link href="https://i.yt.sb/">Tao Yuan</el-link>
          <span class="ind">1</span>,
        </span>
        <span class="author">
          <el-link href="">Xinxiao Wu</el-link>
          <span class="ind">2</span>,
        </span>
        <span class="author">
          <el-link href="https://www.zhusongchun.net/">Song-Chun Zhu</el-link>
          <span class="ind">1,3,5</span>,
        </span>
        <span class="author">
          <el-link href="https://liqing.io/">Qing Li</el-link>
          <span class="ind">1 &#9993;</span>
        </span>
      </div>
      <div class="author-list">
        <span class="org">
          <span class="ind">1</span>
          State Key Laboratory for General Artificial Intelligence, BIGAI
        </span>
        <br>
        <span class="org">
          <span class="ind">2</span>
          Beijing Key Laboratory of Intelligent Information Technology, School of Computer Science & Technology, Beijing Institute of Technology
        </span>
        <br>
        <span class="org">
          <span class="ind">3</span>
          School of Intelligence Science and Technology, Peking University
        </span>
        <span class="org">
          <span class="ind">4</span>
          Shanghai Jiao Tong University
        </span>
        <span class="org">
          <span class="ind">5</span>
          Department of Automation, Tsinghua University
        </span>
      </div>

      <span class="link-block">
        <a href="https://arxiv.org/pdf/" class="external-link button is-normal is-rounded is-dark">
          <span class="icon">
            <svg xmlns="http://www.w3.org/2000/svg" width="1.0em" height="1.0em" viewBox="0 0 24 24">
              <path fill="currentColor"
                d="M3.842 0a1 1 0 0 0-.922.608c-.153.369-.044.627.294 1.111l6.919 8.36l-1.023 1.106a1.04 1.04 0 0 0 .003 1.423l1.23 1.313l-5.44 6.444c-.28.3-.453.823-.297 1.199a1.025 1.025 0 0 0 .959.635a.91.91 0 0 0 .689-.34l5.783-6.126l7.49 8.005a.85.85 0 0 0 .684.26a.96.96 0 0 0 .877-.615c.158-.377-.017-.75-.306-1.14L13.73 13.9l1.064-1.13a.963.963 0 0 0 .009-1.316L4.633.464S4.26.01 3.867 0zm0 .272h.017c.218.005.487.272.564.364l.005.006l.005.005l10.17 10.99a.69.69 0 0 1-.008.946l-1.066 1.133l-1.498-1.772l-8.6-10.39c-.328-.472-.352-.619-.26-.841a.73.73 0 0 1 .671-.44Zm14.341 1.57a.88.88 0 0 0-.655.242l-5.696 6.158l1.694 1.832l5.309-6.514c.325-.433.479-.66.325-1.029a1.12 1.12 0 0 0-.977-.689m-7.655 12.282l1.318 1.414l-5.786 6.13a.65.65 0 0 1-.496.26a.75.75 0 0 1-.706-.467c-.112-.269.036-.687.244-.909l.005-.005l.005-.006z" />
            </svg>
          </span>
          <span>arXiv</span>
        </a>
      </span>
      <span class="link-block">
        <a href="https://github.com/" class="external-link button is-normal is-rounded is-dark">
          <span class="icon">
            <i class="fab fa-github"></i>
          </span>
          <span>Code</span>
        </a>
      </span>

      <!-- Data Link. need changing -->
      <span class="link-block">

        <a target="_blank" href="https://huggingface.co/datasets/"
          class="external-link button is-normal is-rounded is-dark">
          <span class="icon">
            <i class="fa fa-database"></i>
          </span>
          <span>Data</span>
        </a>
      </span>

      <span class="link-block">

        <a target="_blank" href=""
          class="external-link button is-normal is-rounded is-dark">
          <span class="icon">
            <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" width="20" height="20" viewBox="2 0 32 22"
            style="fill:#EBEBEB;">
            <path d="M30.362,8.749c-0.218-1.179-0.989-2.168-2.064-2.647c-0.508-0.228-1.096,0.002-1.32,0.506	c-0.226,0.505,0.001,1.096,0.506,1.32c0.473,0.211,0.814,0.654,0.912,1.185c0.005,0.029,0.009,0.058,0.014,0.087	c0.001,0.093,0.014,0.185-0.002,0.28c-0.145,0.815-0.918,1.362-1.738,1.217c-6.302-1.111-13.09-1.128-20.188-0.053	c-0.518,3.798-0.475,8.104,0.132,11.988c0.127,0.818-0.433,1.586-1.251,1.714c-0.078,0.012-0.156,0.018-0.233,0.018	c-0.361,0-0.699-0.131-0.962-0.353c-0.003-0.002-0.006-0.004-0.008-0.006c-0.119-0.101-0.217-0.226-0.3-0.361	c-0.01-0.017-0.025-0.03-0.035-0.047c-0.085-0.151-0.146-0.319-0.175-0.501c-0.71-4.556-0.697-9.662,0.035-14.01	c0.106-0.632,0.603-1.126,1.233-1.23c0.437-0.073,0.871-0.132,1.306-0.197c5.965-0.766,11.879-0.861,17.592-0.262	c0.567,0.064,1.041-0.342,1.099-0.89c0.058-0.55-0.341-1.042-0.89-1.099C17.738,4.749,11.227,4.896,4.668,5.841	C3.156,6.06,1.93,7.259,1.685,8.759c-0.808,4.979-0.822,9.893-0.043,14.604c0.266,1.597,1.546,2.835,3.113,3.013	c3.665,0.414,7.384,0.621,11.132,0.621c3.772,0,7.575-0.21,11.379-0.63c1.547-0.172,2.827-1.378,3.113-2.934	C31.271,18.569,31.266,13.628,30.362,8.749z M13,13.958c0-0.879,0.944-1.434,1.712-1.007l5.475,3.042c0.79,0.439,0.79,1.576,0,2.015	l-5.475,3.042C13.944,21.476,13,20.92,13,20.042V13.958z"></path>
            </svg>
          </span>
          <span>Video</span>
        </a>
      </span>

    </div>

    <div class="section">
      <el-card class="teaser">
        <el-image src="./tongui/teaser.png"></el-image>
      </el-card>
    </div>


    <div class="section">
      <div class="section-title">Introduction</div>
      <p class="intro">
        Building Graphical User Interface (GUI) agents is a promising research direction, which 
        simulates human interaction with computers or mobile phones to perform diverse GUI tasks. 
        However, a major challenge in developing generalized GUI agents is the lack of sufficient 
        trajectory data across various operating systems and applications, mainly due to the high 
        cost of manual annotations. In this paper, we propose the TongUI framework that builds 
        generalized GUI agents by learning from rich multimodal web tutorials. Concretely, we 
        crawl and process online GUI tutorials (such as videos and articles) into GUI agent 
        trajectory data, through which we produce the GUI-Net dataset containing 143K trajectory 
        data across five operating systems and more than 200 applications. We develop the TongUI 
        agent by fine-tuning Qwen2.5-VL-3B/7B models on GUI-Net, which show remarkable performance 
        improvements on commonly used grounding and navigation benchmarks, outperforming baseline 
        agents about 10% on multiple benchmarks, showing the effectiveness of the GUI-Net dataset 
        and underscoring the significance of our TongUI framework. We will <b>fully open-source</b> 
        the code, the GUI-Net dataset, and the trained models soon.
      </p>
    </div>

    <video width="80%" height=auto controls>
      <source src="/intro.mp4" type="video/mp4">
    </video>


    <div class="section">
      <div class="section-title">Dataset Generation</div>
      <p class="intro"> We design the TongUI framework composed of three steps: tutorial crawling, tutorial processing, and trajectory generation. 
In the tutorial crawling step, we write some seed tasks and use LLMs to extend them into a wider collection of tasks, ensuring comprehensive coverage and enhanced realism of real-world GUI tasks. 
The generated tasks serve as keywords for retrieving content from hosts for online GUI tutorials (such as articles from WikiHow and videos from YouTube).
The tutorial processing step aims to extract the textual descriptions and screenshots of multimodal tutorials.
We first obtain textual descriptions of multimodal tutorials via automatic speech recognition (ASR) or captioning, through which task queries and plans are produced using LLMs on the obtained textual descriptions.
Then, we extract salient frames from videos as the screenshot of each step, while the images in articles are directly regarded as screenshots.
Finally, we leverage one zero-shot GUI agent to automatically recognize trajectories, including reasoning thoughts and actions between two steps.</p>

      <el-card class="teaser">
        <el-image src="./tongui/flow.png"></el-image>
      </el-card>

    </div>

    <div class="section">
      <div class="section-title">Agent Tuning</div>
      <p class="intro"> Based on GUI-Net, we develop the TongUI agent using Qwen2.5-VL-3B/7B models. 
      The architecture of the used model is shown below.
      </p>

      <el-card class="teaser">
        <el-image src="./tongui/network.png"></el-image>
      </el-card>

    </div>


    <div class="section">
      <div class="section-title">GUI-Net Dataset </div>
      <div class="intro">Based on the tutorial collection pipeline, we construct a GUI-Net dataset that contains 143K data across five operating systems with more than 200 applications. 
        <br>
        We show the <b>operating system distribution</b> in (a). Our dataset covers a diverse range of operating systems, including Windows, Android, iOS, MacOS, and Linux, ensuring a broad representation of GUI interactions across both desktop and mobile environments.
The <b>application distribution</b> is shown in (b). Our dataset covers a wide variety of application categories, ensuring a broad and diverse range of user tasks.
We show the <b>step distribution</b> in (c). Our dataset includes GUI interactions with varying step lengths, ranging from single-step actions to 9-step tasks. The distribution shows that shorter tasks (1-3 steps) are more frequent, while longer tasks gradually decrease in numbers. This distribution reflects a balance between simple and complex GUI interactions, capturing both quick actions and more involved workflows. 
The <b>action distribution</b> is shown in (d). Our dataset encompasses a diverse range of GUI actions, with Click and Tap being the most frequent, reflecting their central role in both desktop and mobile interactions. Other common actions include HotKey, Swipe, and Drag, covering various forms of user interactions.

      </div>

      <br>
      <el-card class="teaser">
        <el-image src="./tongui/dataset_statistics.png"></el-image>
      </el-card>
    </div>

    <div class="section">
      <div class="section-title">Evaluation and Results </div>
      <div class="intro">We evaluate the TongUI agent on offline benchmarks: <b>ScreenSpot</b>, <b>AITW</b>, <b>Mind2Web</b>, and <b>Baidu Experience</b> (we manually annotate 102 data points from the collected Baidu Experience data for testing). We also evaluate the TongUI agent on one online benchmark: <b>MiniWob</b>.
The results show that the TongUI agent exhibits consistent improvements in grounding and navigation capabilities. 
The results demonstrate the generalization of the TongUI agent, since it is trained on high-quality data across diverse applications, underscoring the effectiveness of the TongUI framework that improves the agents in a low-cost manner without the need for expensive manual annotation.<br></div>

      <div class="intro"><b>Metric.</b> After training, we perform zero-shot evaluation of the model's grounding capability on ScreenSpot. 
      The annotation of ScreenSpot gives a bounding box for each interactive element. 
      The action from the model is considered correct when the point predicted falls within the bounding box. 
      For online evaluations, the environment of MiniWob provides reward functions, which suggests if a trajectory is correct. 
      For offline evaluations such as Mind2Web, AITW, and Baidu Experience, the model will be asked to output actions with parameters. 
      We evaluate if the action is correct by the exact match. For parameters, we do the exact match for string parameters and check if a point parameter falls within the bounding box based on annotations. 
      We evaluate the model after fine-tuning on Mind2Web, AITW, and MiniWob.
      In other evaluation datasets, we use the pre-trained model.<br><br>
      </div>

      <div class="intro"><b>ScreenSpot Results.</b> In Table 1, we show the zero-shot grounding performance of TongUI. Similar to previous works, grounding on icon is much harder than grounding on text. 
The collected data leads to significant improvements on the baseline Qwen2.5-VL model. 
Compared with ShowUI, we use similar training data size, but it has about 4.5 % improvements.
TongUI has a slightly worse performance than UI-TARS (3% on the 3B model and 6% on the 7B model), but the training data used by UI-TARS is 40 times that of ours, causing more resource consumption.
These results demonstrate that GUI-Net can indeed improve the grounding capability of GUI agents.<br></div>
      <el-card class="stats-img-1">
        <el-image src="./tongui/results_screenspot.png"></el-image>
      </el-card>

      <div class="intro"><b>AITW  Results.</b> AITW is a dataset about navigation on Android. The comparisons are shown in Table 2.
We observe that the fine-tuned TongUI-3B model achieves better performance compared to ShowUI-2B by 1.6% in overall success rate. This shows that the collected data also improves the reasoning and planning capabilities of GUI agents on the navigation tasks. 
The larger model, TongUI-7B, gains 1.7% improvement compared to TongUI-3B, which is consistent with common sense. <br></div>
      <el-card class="stats-img-1">
        <el-image src="./tongui/results_aitw.png"></el-image>
      </el-card>

      <div class="intro"><b>Mind2Web Results.</b> In Table 3, the results of web navigation show that TongUI achieves the best performance on all metrics.
Notably, cross-task, cross-website, and cross-domain tasks are more difficult than conventional GUI tasks. This highlights that the collected data improves the generalization capability of GUI agents. 
We argue that the reason is that the collected data involves diverse applications and operating systems, improving the generalization capability.
Compared to ShowUI-2B, TongUI-3B has obvious improvements, especially on <em>Elem. Acc</em> and <em>Step SR</em>. 
Compared with ShowUI-Qwen2.5-VL-3B that fine-tunes the Qwen2.5-VL-3B model using the ShowUI dataset, TongUI-3B also has better performance (3.2% improvements), showing the quality of our data.<br></div>
      <el-card class="stats-img-1">
        <el-image src="./tongui/results_mind2web.png"></el-image>
      </el-card>
    </div>

    <div class="section">
      <div class="section-title">Video Demo</div>

      <video height="800" controls>
        <source src="/video.mp4" type="video/mp4">
      </video>

      <p class="intro">
        
      </p>

      <video width="700" height=auto controls>
        <source src="/video1.mp4" type="video/mp4">
      </video>
    </div>

  </div>


  <section class="section" id="BibTeX" style="text-align: left;">
    <div class="container is-max-desktop content" style="max-width: 100%; margin: 0 auto;">
      <h3 class="title" style="font-size: small;">
        BibTeX
      </h3>
      <div class="bibtex-container">
        <pre><code class="language-bibtex">
    
</code></pre>
      </div>
    </div>
  </section>

</template>



<style scoped>
.main {
  text-align: center;
  color: #333;
}

.header {
  margin: 60px 0 0 0 !important;
}

.title {
  font-size: 5em;
}

.subtitle {
  font-size: 2.5em;
  color: #555;
}

.author-list {
  margin-top: 20px;
}

.author a {
  font-size: 1.2em;
  font-weight: normal;
  color: #337ecc;
}

.org {
  margin: 0 4px 0 4px;
}

.ind {
  font-size: 0.8em;
  vertical-align: super;
}

.section {
  margin: 50px 0;
}

.tldr {
  text-align: left;
  font-size: 1em;
  max-width: 1360px;
  line-height: 150%;
}

.section-title {
  margin: 20px;
  font-size: 2em;
  font-weight: bold;
}

.conference {
  text-align: center;
  margin: 20px;
  font-size: 1.5em;
  color: #665;
}

.uns {
  text-decoration: underline;
}

.mat-icon {
  width: 0.8em;
  height: 0.8em;
  margin-right: 0.2em;
}

.teaser {
  max-width: 840px;
  margin: 0 auto;
}

.stats-img {
  height: 300px;
}

.stats-img-1 {
  max-width: 67%;
  max-height: 95%;
  object-fit: contain;
  margin: 0 auto;
  display: block;
}

.intro {
  text-align: justify;
  font-size: 1em;
  max-width: 1360px;
  line-height: 150%;
}

.link-block a {
  margin-top: 5px;
  margin-bottom: 5px;
}

.example-dialog {
  width: 800px;
}

.footer {
  color: #aaa;
  margin: 100px 0 60px 0;
}


/* The top button */
.external-link {
  display: inline-block;
  padding: 8px 16px;
  /* inner margin */
  margin: 4px;
  /* outer margin */
  border: 1px solid #9a9c9e;
  /* color of border */
  border-radius: 9px;
  background-color: #8a8b8b;
  color: white;
  text-decoration: none;
  font-size: 20px;
  transition: background-color 0.3s;
}

.external-link:hover {
  background-color: #8e8f90;
}

.external-link .icon {
  margin-right: 8px;
}

.external-link .fas {
  font-size: 18px;
}

.bibtex-container {
  background-color: #e1e4e9;
  /* Change background color to match the theme */
  padding: 1em;
  /* Add padding for better readability */
  border-radius: 5px;
  /* Add border radius for rounded corners */
  text-align: left;
  white-space: pre;
  /* Preserve formatting and prevent line breaks */
  overflow-x: auto;
  /* Add horizontal scroll bar */
}

pre {
  margin: 0;
}

code {
  font-family: 'Courier New', Courier, monospace;
  /* Change font to monospace */
  color: #0a0b0b;
  /* Change text color to match the theme */
}
</style>
