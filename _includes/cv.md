 I am a computational biologist, working towards my doctoral degree with Lorin Crawford, Ph.D. and I also collaborate with Ritambhara Singh, Ph.D.  
My masters degree advisor was Sorin Istrail, Ph.D. <br><br>


## <i class="fa fa-chevron-right"></i> Education

<table class="table table-hover">
  <tr>
    <td class="col-md-3">September 2018 - May 2023</td>
    <td>
        <strong>Ph.D. in Computer Science and Computational Biology</strong>
          (0.00/0.00)
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
  <td><strong>Microsoft Research: Genomics</strong>, Incoming Research Intern (Redmond, WA)</td>
</tr>
<tr>
</tr>
<tr>
  <td class='col-md-3'>May 2017 - Sep 2018</td>
  <td><strong>Massachusetts Institute of Technology</strong>, Research Associate (Cambridge, MA)</td>
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
<td class="col-md-3"><a href='https://www.biorxiv.org/content/10.1101/2020.04.28.066787v1' target='_blank'><img src="images/publications/HAPLEX.png"/></a> </td>
<td>
    <strong>Gromov-Wasserstein Optimal Transport to Align Single-Cell Multi-Omics Data</strong><br>
    <strong>P. Demetci*</strong>, R. Santorella*, B. Sandstede, W. Stafford Noble and Ritambhara Singh# <br>
     *Equal Contribution, #Corresponding Author<br>
    bioRxiv, 2020<br>
    
    [1] 
[<a href='javascript:;'
    onclick='$("#abs_alpaydemetci").toggle()'>abs</a>] [<a href='https://www.biorxiv.org/content/10.1101/2020.04.28.066787v1' target='_blank'>pdf</a>] <br>
    
<div id="abs_alpaydemetci" style="text-align: justify; display: none" markdown="1">
Data integration of single-cell measurements is critical for our understanding of cell development and disease, but the lack of correspondence between different types of single-cell measurements makes such efforts challenging. Several unsupervised algorithms are capable of aligning heterogeneous types of single-cell measurements in a shared space, enabling the creation of mappings between single cells in different data modalities.
We present Single-Cell alignment using Optimal Transport (SCOT), an unsupervised learning algorithm that uses Gromov Wasserstein-based optimal transport to align single-cell multi-omics datasets. SCOT calculates a probabilistic coupling matrix that matches cells across two datasets. The optimization uses k-nearest neighbor graphs, thus preserving the local geometry of the data. We use the resulting coupling matrix to project one single-cell dataset onto another via a barycentric projection.  We compare the alignment performance of SCOT with state-of-the-art algorithms on three simulated and two real datasets. Our results demonstrate that SCOT yields results that are comparable in quality to those of competing methods, but SCOT is significantly faster and requires tuning fewer hyperparameters. The code is available at <a href='https://github.com/rsinghlab/SCOT' target='_blank'>https://github.com/rsinghlab/SCOT</a>
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
    
    [1] 
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
    
    [1] 
[<a href='javascript:;'
    onclick='$("#abs_parkerdemetci").toggle()'>abs</a>] [<a href='https://jb.asm.org/content/early/2019/07/03/JB.00259-19/figures-only?versioned=true' target='_blank'>pdf</a>] <br>
    
<div id="abs_parkerdemetci" style="text-align: justify; display: none" markdown="1">
Expression of motility genes is a potentially beneficial but costly process in bacteria. Interestingly, many isolate strains of _Escherichia coli_ possess motility genes but have lost the ability to activate them in conditions in which motility is advantageous, raising the question of how they respond to these situations. Through transcriptome profiling of strains in the _E. coli_ single-gene knockout Keio collection, we noticed drastic upregulation of motility genes in many of the deletion strains as compared to its weakly motile parent strain (BW25113). We show that this switch to a motile phenotype is not a direct consequence of the genes deletec, but is instead due to a variety of secondary mutations that increase the expression of the major motility regulator, FlhDC. Importantly, we find that this switch can be reproduced by growing poorly motile _E. coli_ strains in non-shaking liquid medium overnight but not in shaking liquid medium. Individual isolates after the non-shaking overnight incubations acquired distinct mutations upstream of the _flhDC_ operon, including different insertion sequence (IS) elements and, to a lesser extent, point mutations. The rapid sweep in the non-shaking population shows that poorly motile strains can quickly adapt to a motile lifestyle by genetic rewiring. 
</div>
</td>
</tr>

</table>


## <i class="fa fa-chevron-right"></i> Teaching Experience
<table class="table table-hover">
<tr>
  <td class='col-md-1'>S2019</td>
  <td><strong>Advanced Algorithms in Computational Biology and Medical Bioinformatics</strong> (CSCI 2820 @ Brown U.), Teaching Assistant</td>
</tr>
<tr>
  <td class='col-md-1'>F2016</td>
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

## <i class="fa fa-chevron-right"></i> Membership, Community, Professional Service
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
</table>
