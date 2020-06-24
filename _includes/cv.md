I am a computational biologist, working towards my doctoral degree with [Lorin Crawford, Ph.D.](lcrawlab.com) and I also closely collaborate with [Ritambhara Singh, Ph.D. ](rsinghlab.org). My masters degree advisor was [Sorin Istrail, Ph.D.](vivo.brown.edu/display/sistrail). Types of research problems I currently work on include (1) manifold alignment and optimal transport algorithms for single-cell multi-omic data integration, and (2) Bayesian machine learning models for multi-scale genomic association discovery. <br>  

Before joining Brown University for my Ph.D., I received my bachelor’s degree in bioengineering from [Olin College of Engineering](http://www.olin.edu/). There, I worked with [Jean J. Huang, Ph.D.](http://www.olin.edu/faculty/profile/jean-j-huang/) and [John Geddes, Ph.D.](http://www.olin.edu/faculty/profile/john-b-geddes) on mathematical models and bioinformatic analyses of environmental microbial communities. Then, I spent a year in [Li Quantitative Biology Lab](http://gwli.scripts.mit.edu/group/?p=737) at <a href="https://www.mit.edu/"> Massachusetts Institute of Technology (MIT) <\a>, working as a research support associate and lab manager under the supervision of <a href="https://biology.mit.edu/profile/gene-wei-li/"> Gene-Wei Li, Ph.D. <\a> My work there mostly involved investigating regulatory network rewiring in E.coli gene knock-out strains, as well as assissting graduate students with various quantitative biology research projects. <br>

Currently, I am working in <a href="https://www.microsoft.com/en-us/research/research-area/medical-health-genomics/?facet%5Btax%5D%5Bmsr-research-area%5D%5B0%5D=13553&sort_by=most-recent"> the Genomics team <\a> at <a href="https://www.microsoft.com/en-us/research/lab/microsoft-research-redmond/"> Microsoft Research (Redmond, WA) <\a>  as a research intern and I am really enjoying it! <br>
My e-mail is pinardemetci at gmail dot com if you'd like to talk. <br>


## <i class="fa fa-chevron-right"></i> Education

<table class="table table-hover">
  <tr>
    <td class="col-md-3">September 2018 - May 2023</td>
    <td>
        <strong>Ph.D. in Computer Science and Computational Biology</strong>
          (3.90/4.00)
        <br>
      Brown University (Providence, RI)
    </td>
  </tr>
  <tr>
    <td class="col-md-3">September 2018 - May 2020</td>
    <td>
        <strong>M.Sc. in Computer Science</strong>
          (4.00/4.00)
        <br>
      Brown University (Providence, RI)
    </td>
  </tr>
  <tr>
    <td class="col-md-3">September 2013 - May 2017</td>
    <td>
        <strong>B.Sc. in Bioengineering</strong>
          (3.67/4.00)
        <br>
      Olin College of Engineering (Needham, MA)
    </td>
  </tr>
  <tr>
    <td class="col-md-3">September 2008 - June 2013</td>
    <td>
      TEVITOL High School + IB Diploma (Gebze, Turkey)
    </td>
  </tr>
</table>


## <i class="fa fa-chevron-right"></i> Professional Experience
<table class="table table-hover">
<tr>
  <td class='col-md-3'>June 2020 - Sep 2020</td>
  <td><strong>Microsoft Research: Genomics</strong>, Research Intern (Redmond, WA)</td>
</tr>
<tr>
</tr>
<tr>
  <td class='col-md-3'>May 2017 - Sep 2018</td>
  <td><strong>Massachusetts Institute of Technology</strong>, Research Support Associate (Cambridge, MA)</td>
</tr>
<tr>
  <td class='col-md-3'>Jan 2016 - Oct 2016</td>
  <td><strong>Daktari Diagnostics</strong>, Student Engineer (Cambridge, MA)</td>
</tr>
<tr>
</tr>
</table>


## <i class="fa fa-chevron-right"></i> Research Projects and Publications <a href=""><i class="fa fa-code-fork" aria-hidden="true"></i></a>

<a href="https://scholar.google.com/citations?user=0Tzd6eAAAAAJ&hl=en" class="btn btn-primary" style="padding: 0.3em;">
  <i class="ai ai-google-scholar"></i> Google Scholar
</a>

<table class="table table-hover">
<tr>
<td class="col-md-3"><a href='https://www.biorxiv.org/content/10.1101/2020.04.28.066787v1' target='_blank'><img src="images/publications/SCOT.png"/></a> </td>
<td>
    <strong>Gromov-Wasserstein Optimal Transport to Align Single-Cell Multi-Omics Data</strong><br>
    <strong>P. Demetci*</strong>, R. Santorella*, B. Sandstede, W. Stafford Noble and Ritambhara Singh# <br>
     *Equal Contribution, #Corresponding Author<br>
    bioRxiv, 2020<br>
    
    [4] 
[<a href='javascript:;'
    onclick='$("#abs_demetcisantorella").toggle()'>abs</a>] [<a href='https://www.biorxiv.org/content/10.1101/2020.04.28.066787v1' target='_blank'>pdf</a>] <br>
    
<div id="abs_demetcisantorella" style="text-align: justify; display: none" markdown="1">
Data integration of single-cell measurements is critical for our understanding of cell development and disease, but the lack of correspondence between different types of single-cell measurements makes such efforts challenging. Several unsupervised algorithms are capable of aligning heterogeneous types of single-cell measurements in a shared space, enabling the creation of mappings between single cells in different data modalities.
We present Single-Cell alignment using Optimal Transport (SCOT), an unsupervised learning algorithm that uses Gromov Wasserstein-based optimal transport to align single-cell multi-omics datasets. SCOT calculates a probabilistic coupling matrix that matches cells across two datasets. The optimization uses k-nearest neighbor graphs, thus preserving the local geometry of the data. We use the resulting coupling matrix to project one single-cell dataset onto another via a barycentric projection.  We compare the alignment performance of SCOT with state-of-the-art algorithms on three simulated and two real datasets. Our results demonstrate that SCOT yields results that are comparable in quality to those of competing methods, but SCOT is significantly faster and requires tuning fewer hyperparameters. The code is available at <a href='https://github.com/rsinghlab/SCOT' target='_blank'>https://github.com/rsinghlab/SCOT</a>
</div>

</td>
</tr>


<tr>
<td class="col-md-3"><a href='https://www.biorxiv.org/content/10.1101/2020.04.28.066787v1' target='_blank'><img src="images/publications/SCOT.png"/></a> </td>
<td>
    <strong> Unsupervised Manifold Alignment for Single-Cell Multi-Omics Data</strong><br>
    R. Singh#<strong>P. Demetci</strong>, G. Bonora, V. Ramani, C. Lee, H. Fang, Z. Duan, X. Deng, J. Shendure, C. Disteche and W. Stafford Noble#<br>
     #Corresponding Authors<br>
    ACM-BCB, 2020<br>
    
    [4] 
[<a href='javascript:;'
    onclick='$("#abs_demetcisantorella").toggle()'>abs</a>] [<a href='https://www.biorxiv.org/content/10.1101/2020.04.28.066787v1' target='_blank'>pdf</a>] <br>
    
<div id="abs_demetcisantorella" style="text-align: justify; display: none" markdown="1">
Integrating single-cell measurements that capture different properties of the genome is vital to extending our understanding of genome biology.This task is challenging due to the lack of a shared axis across datasets obtained from different types of single-cell experiments. For most such datasets, we lack corresponding information among the cells (samples) and the measurements (features). In this scenario, unsupervised algorithms that are capable of aligning single-cell experiments are critical to learning an in silico co-assay that can help draw correspondences among the cells.Maximum mean discrepancy-based manifold alignment (MMD-MA) is such an unsupervised algorithm. Without requiring correspondence information, it can align single-cell datasets from different modalities in a common shared latent space, showing promising results on simulations and a small-scale single-cell experiment with 61 cells.However, it is essential to explore the applicability of this method to larger single-cell experiments with thousands of cells so that it can be of practical interest to the community.In this paper, we apply MMD-MA to two recent datasets that measure transcriptome and chromatin accessibility in ~2000 single cells. To scale the runtime of MMD-MA to a more substantial number of cells, we extend the original implementation to run on GPUs. We also introduce a method to automatically select one of the user-defined parameters, thus reducing the hyperparameter search space. We demonstrate that the proposed extensions allow MMD-MA to accurately align state-of-the-art single-cell experiments.
</div>

</td>
</tr>


<tr>
<td class="col-md-3"><a href='https://www.iscb.org/cms_addon/conferences/ismb2020/proceedings.php' target='_blank'><img src="images/publications/HAPLEX.png"/></a> </td>
<td>
    <strong>Combinatorial and statistical prediction of gene expression from haplotype sequence</strong><br>
    B. Alpay*, <strong>P. Demetci*</strong> Sorin Istrail, and Derek Aguiar# <br>
     *Equal Contribution, #Corresponding Author<br>
    ISMB Proceedings, 2020<br>
    
    [3] 
[<a href='javascript:;'
    onclick='$("#abs_alpaydemetci").toggle()'>abs</a>] [<a href='https://www.iscb.org/cms_addon/conferences/ismb2020/proceedings.php' target='_blank'>pdf</a>] <br>
    
<div id="abs_alpaydemetci" style="text-align: justify; display: none" markdown="1">
Genome-wide association studies (GWAS) have discovered thousands of significant genetic effects on disease phenotypes.By considering gene expression as the intermediary between genotype and disease phenotype, eQTL studies have interpreted many of these variants by their regulatory effects on gene expression. However, there remains a considerable gap between genotype-to-gene expression association and genotype-to-gene expression prediction. Accurate prediction of gene expression enables gene-based association studies to be performed post-hoc for existing GWAS, reduces multiple testing burden, and can prioritize genes for subsequent experimental investigation.In this work, we develop gene expression prediction methods that relax the independence and additivity assumptions between genetic markers. First, we consider gene expression prediction from a regression perspective and develop the HAPLEXR algorithm which combines haplotype clusterings with allelic dosages. Second, we introduce the new gene expression classification problem, which focuses on identifying expression groups rather than continuous measurements; we formalize the selection of an appropriate number of expression groups using the principle of maximum entropy. Third, we develop the HAPLEXD algorithm that models haplotype sharing with a modified suffix tree data structure and computes expression groups by spectral clustering. In both models, we penalize model complexity by prioritizing genetic clusters that indicate significant effects on expression. We compare HAPLEXR and HAPLEXD with three state-of-the-art expression prediction methods and two novel logistic regression approaches across five GTEx v8 tissues. HAPLEXD exhibits significantly higher classification accuracy overall; HAPLEXR shows higher prediction accuracy on approximately half of the genes tested and the largest number of best predicted genes ($r^2>0.1$) among all methods.
We show that variant and haplotype features selected by HAPLEXR are smaller in size than competing methods (and thus more interpretable) and are significantly enriched in functional annotations related to gene regulation. These results demonstrate the importance of explicitly modelling non-dosage dependent and intragenic epistatic effects when predicting expression.
</div>

</td>
</tr>

<tr>
<td class="col-md-3"><a href='https://jb.asm.org/content/early/2019/07/03/JB.00259-19/figures-only?versioned=true' target='_blank'><img src="images/publications/ecoli.png"/></a> </td>
<td>
    <strong>Rapid accumulation of motility-activating mutations in resting liquid culture of _Escherichia coli_</strong><br>
    D. Parker*, <strong>P.Demetci*</strong>, and G.W. Li# <br>
     *Equal Contribution,  #Corresponding Author<br>
    Journal of Bacteriology, 2019<br>
    
    [2] 
[<a href='javascript:;'
    onclick='$("#abs_parkerdemetci").toggle()'>abs</a>] [<a href='https://jb.asm.org/content/early/2019/07/03/JB.00259-19/figures-only?versioned=true' target='_blank'>pdf</a>] <br>
    
<div id="abs_parkerdemetci" style="text-align: justify; display: none" markdown="1">
Expression of motility genes is a potentially beneficial but costly process in bacteria. Interestingly, many isolate strains of _Escherichia coli_ possess motility genes but have lost the ability to activate them in conditions in which motility is advantageous, raising the question of how they respond to these situations. Through transcriptome profiling of strains in the _E. coli_ single-gene knockout Keio collection, we noticed drastic upregulation of motility genes in many of the deletion strains as compared to its weakly motile parent strain (BW25113). We show that this switch to a motile phenotype is not a direct consequence of the genes deletec, but is instead due to a variety of secondary mutations that increase the expression of the major motility regulator, FlhDC. Importantly, we find that this switch can be reproduced by growing poorly motile _E. coli_ strains in non-shaking liquid medium overnight but not in shaking liquid medium. Individual isolates after the non-shaking overnight incubations acquired distinct mutations upstream of the _flhDC_ operon, including different insertion sequence (IS) elements and, to a lesser extent, point mutations. The rapid sweep in the non-shaking population shows that poorly motile strains can quickly adapt to a motile lifestyle by genetic rewiring. 
</div>
</td>
</tr>

<tr>
<td class="col-md-3"><a href='https://ieeexplore.ieee.org/abstract/document/7757463' target='_blank'><img src="images/publications/ecoli.png"/></a> </td>
<td>
    <strong>Internalization and externalization in the classroom: How do they emerge and why is it important?</strong><br>
     <strong>P.Demetci</strong>, C. Nichols, Y. V. Zastavker, J. D. Stolk, A. Dillon, M. D. Gross.<br>
    IEEE, 2016<br>
    FIE Conference, 2016<br>
    
    [1] 
[<a href='javascript:;'
    onclick='$("#abs_demetcinichols").toggle()'>abs</a>] [<a href='https://ieeexplore.ieee.org/abstract/document/7757463'  target='_blank'>pdf</a>] <br>  
<div id="abs_demetcinichols" style="text-align: justify; display: none" markdown="1">
“I felt so dumb, and it's not fair that I cannot grasp this information to save my life, and other people can with no problem.” Why do some students feel empowered in the classroom, and feel they have control over their own learning, while others do not? Our qualitative investigation is a part of a larger mixed-methods study about students' situational motivations in introductory STEM courses. We used grounded theory to analyze students' responses to surveys about emotion, course relevance, and motivation. We investigated two emergent phenomena we called “internalization” and “externalization.” Our definitions of these are based on a student's perception of who or what influences the outcomes of their activities: the students themselves, or external factors such as the instructor, peers, or the educational system as a whole. Our findings indicate that (1) internalization correlates with cognitive autonomy, students' perception of course content having high personal relevance, and group projects in project-based learning environments; and (2) externalization correlates with lecture-based environments and students' perceptions of lack of personal relevance in the course content. Our analyses suggest that project-based learning environments may serve to empower students, but only when course content is found to be relevant.
</div>
</td>
</tr>

</table>

## <i class="fa fa-chevron-right"></i> Invited Talks, Conferences, Oral and Poster Presentations
<table class="table table-hover">
<tr>
  <td class='col-md-1'>2020</td>
  <td><strong>ISMB Proceedings </strong> Combinatorial and statistical prediction of gene expression from haplotype sequence  <br>
  Berk Alpay*, Pinar Demetci*, Sorin Istrail, Derek Aguiar, *Equal contribution</td>
</tr>
<tr>
  <td class='col-md-1'>2020</td>
  <td><strong>ISMB (Oral & Poster Presentation)</strong> Gromov-Wasserstein Optimal Transport to Align Single-Cell Multi-Omics Data  <br>
  Pinar Demetci*, Rebecca Santorella*, Bjorn Sandstede, William Stafford Noble, Ritambhara Singh, *Equal contribution</td>
</tr>
<tr>
  <td class='col-md-1'>2019</td>
  <td><strong>CCV-Con (Invited Talk @ Brown University) </strong> Biologically Annotated Neural Networks for Multi-scale Genomic Association Discovery  <br>
  Pinar Demetci, Wei Cheng, Greg Darnell, Sohini Ramachandran, Lorin Crawford</td>
</tr>
<tr>
  <td class='col-md-1'>2016</td>
  <td><strong>FIE (Oral Presentation) </strong> Internalization and externalization: How do they emerge and why is it important?  <br>
  P.Demetci, C. Nichols, Y. V. Zastavker, J. D. Stolk, A. Dillon, M. D. Gross.</td>
</tr>
<tr>
  <td class='col-md-1'>2016</td>
  <td><strong>NEMPET (Poster Presentation) </strong> Bioinformatic Comparison of Phototrophic Communitiesthat Degrade Cellulose and Fix Nitrogen  <br>
  Pinar Demetci, Michael Sheets, Anna Knapp, Linda Amaral-Zettler, Jean Huang</td>
</tr>
<tr>
  <td class='col-md-1'>2015</td>
  <td><strong>Closing the Gap (Oral Presentation) </strong> Project EyeHelper: Assistive Navigation for Blind Shopping  <br>
  Pinar Demetci, Anders Johnnson, Matthew Ruehle, Paul Ruvolo</td>
</tr>
</table>


## <i class="fa fa-chevron-right"></i> Teaching Experience
<table class="table table-hover">
<tr>
  <td class='col-md-1'>Spring 2019</td>
  <td><strong>Advanced Algorithms in Computational Biology and Medical Bioinformatics</strong> (CSCI 2820 @ Brown U.), Teaching Assistant</td>
</tr>
<tr>
  <td class='col-md-1'>Fall 2016</td>
  <td><strong>Designing Better Drugs </strong> (SCI1240 @ Olin College), Teaching Assistant and Laboratory Assistant</td>
</tr>
</table>


## <i class="fa fa-chevron-right"></i> Honors & Awards
<table class="table table-hover">
<tr>
  <td class='col-md-2'>2018 - 2020</td>
  <td>
    Brown Graduate Fellowship
    <!--  -->
  </td>
</tr>
<tr>
  <td class='col-md-2'>2016</td>
  <td>
    <a href="https://www.comap.com/undergraduate/contests/mcm/contests/2016/results/2016-ICM_Problem-F-Results.pdf">Meritorius Winner: 2016 MCM/ICM Interdisciplinary Contest in Mathematical Modeling</a>
    <!--  -->
  </td>
</tr>
<tr>
  <td class='col-md-2'>2015-2017</td>
  <td>
    Olin Alumni Scholarship
    <!--  -->
  </td>
</tr>
<tr>
  <td class='col-md-2'>2013-2017</td>
  <td>
    <a href="http://impact.olin.edu/2017/scholarships#scholarships">Sunlin Chou International Scholarship (50% tuition)</a>
    <!--  -->
  </td>
</tr>
<tr>
  <td class='col-md-2'>2013-2017</td>
  <td>
    Olin Merit Scholarship (50% tuition)
    <!--  -->
  </td>
</tr>

<tr>
  <td class='col-md-2'>2013</td>
  <td>
    <a href="http://info.ifpan.edu.pl/firststep/results/21">Honorable Mention (Instrumentation): First Step to Nobel Prize in Physics</a>
    <!--  -->
  </td>
</tr>
</table>

## <i class="fa fa-chevron-right"></i> Professional Service and Community Memberships
<table class="table table-hover">
  <tr>
    <td class='col-md-2'>Member</td>
    <td>
      International Society for Computational Biology (ISCB)
      <!--  -->
    </td>
  </tr>
  <tr>
    <td class='col-md-2'>Member</td>
    <td>
      Models, Inference, and Algorithms (MIA) at Broad Institute
      <!--  -->
    </td>
  </tr>
  <tr>
    <td class='col-md-2'>Member</td>
    <td>
      Graduate Women in Science and Engineering @ Brown University
      <!--  -->
    </td>
  </tr>
</table>

## <i class="fa fa-chevron-right"></i> Skills
<table class="table table-hover">
  <tr>
    <td class='col-md-2'>Programming Languages</td>
    <td>
      Python, R, Java, C++ 
      <!--  -->
    </td>
  </tr>
    <tr>
    <td class='col-md-2'>Frameworks</td>
    <td>
      NumPy, Pandas, PyTorch, SciPy, TensorFlow, HDF5, Bioconductor
      <!--  -->
    </td>
  </tr>
    <tr>
    <td class='col-md-2'>Systems</td>
    <td>
      Linux, OSX
      <!--  -->
    </td>
  </tr>
    <tr>
    <td class='col-md-2'>Bioinformatics Tools</td>
    <td>
      VCFtools, BEDtools, PLINK, Cytoscape, QIIME, VAMPS, JGI
      <!--  -->
    </td>
  </tr>
      <tr>
    <td class='col-md-2'>Natural Languages</td>
    <td>
      English (proficient - TOEFL: 115/120), Turkish (native language), French (A2)
      <!--  -->
    </td>
  </tr>
        <tr>
    <td class='col-md-2'>Laboratory</td>
    <td>
      DNA & RNA Extraction, PCR & RT-qPCR, Electrophoresis & PAGE, Western blotting, Molecular transformation, 
      <!--  -->
    </td>
  </tr>
</table>
