# Python Optimal Transport - POT package

### Collected by Pang Bo

## Optimal transport introduction
Introduced by Gaspard Monge in the 19th century, optimal transport (OT) reappeared in the work of Kantorovitch and recently found surprising new developments in a wide range of fields, including computational fluid mechanics, color transfer between multiple images or warping in the context of image processing, interpolation schemes or distance computation on meshes in computer graphics, and economics, via matching and equilibrium problems. Fundamentally, OT provides means of defining distances between probability measures defined in potentially high-dimensional metric spaces. These distances, which have received several names in the literature (Wasserstein, Monge-Kantorovich or Earth Mover distances), have strong and important properties:   
- they can be evaluated when only empirical measures of the distributions are observed, and do not require estimating parametric or semi-parametric distributions as a preprocess;   
- they can exploit the geometry of the underlying metric space, and provide meaningful distances even when the supports of the distributions do not overlap.
![image](https://github.com/Pangbo15/SIQEF-RA-2020/blob/master/SIQEF%20Assignment/pot/POT%20Intro.png)

You can have more guidence in 
https://pot.readthedocs.io/en/gromov/index.html


##　Reference　
We refer the Jupyter cases from
https://pythonot.github.io/auto_examples/index.html
https://github.com/rflamary/OTML_DS3_2018
https://github.com/QuantEcon/columbia_mini_course/blob/master/
http://alfredgalichon.com/mec_optim_archive_2019-01/
https://github.com/mlss-skoltech/tutorials/tree/master/optimal_transport_tutorial


The tutorial folder contains the lecture from Prof.Marco Cuturi is more novice-friendly. We suggest you to read it and try to finish the initial 'TO DO' problems before you check the answers. After you have some basic knowledge, you may go through the official cases in another folder.


You can find other interesting examples in the material prepared by Alfred Galichon at

http://alfredgalichon.com/mec_optim_archive_2019-01/


## Tutorial

EMD(Wasserstein) distance self-study materials:


English:
https://github.com/mlss-skoltech/lectures/tree/master/optimal_transport
https://wp-en.wikideck.com/Transportation_theory_(mathematics)
https://optimaltransport.github.io/slides/
https://ljk.imag.fr/membres/Emmanuel.Maitre/lib/exe/fetch.php?media=b07.stflour.pdf
https://www.youtube.com/watch?v=ymWDGzpQdls
https://victorzhaoblog.wordpress.com/2019/04/13/wasserstein-distance-vs-dynamic-time-warping/   Wasserstein vs DTW
https://arxiv.org/abs/1904.08994    (Relative paper)
https://vincentherrmann.github.io/blog/wasserstein/
https://en.wikipedia.org/wiki/Frobenius_inner_product  (Useful detailed knowledge about inner product)
https://github.com/zhangqianhui/AdversarialNetsPapers  (GAN Paper)
https://arxiv.org/abs/1701.07875    (GAN Paper)


Chinese:
https://blog.csdn.net/Utterly_Bonkers/article/details/88387081 
https://zhuanlan.zhihu.com/p/84617531   
https://zhuanlan.zhihu.com/p/145739750    
https://mp.weixin.qq.com/s?__biz=MzIwMTc4ODE0Mw==&mid=2247484880&idx=1&sn=4b2e976cc715c9fe2d022ff6923879a8&chksm=96e9da50a19e5346307b54f5ce172e355ccaba890aa157ce50fda68eeaccba6ea05425f6ad76&scene=21#wechat_redirect  
https://kexue.fm/archives/6280  
https://zhuanlan.zhihu.com/p/93853664 
https://zhuanlan.zhihu.com/p/74641429   (OP in Econometrics) 
https://blog.csdn.net/Utterly_Bonkers/article/details/88860704?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522159670332019724839251818%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=159670332019724839251818&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v3~pc_rank_v3-13-88860704.pc_ecpm_v3_pc_rank_v3&utm_term=python+optimal+transport&spm=1018.2118.3001.4187


Introduction to optimal transport video
https://www.youtube.com/watch?v=kjOBJP7gglw&list=PLJ6garKOlK2qKVhRm6UwvcQ46wK-ciHbl&pbjreload=101


Courses and practical sessions for the Optimal Transport and Machine learning course at http://www.ds3-datascience-polytechnique.fr.
The course has been prepared by [Marco Cuturi](http://marcocuturi.net/),
 [Rémi Flamary](http://remi.flamary.com/) and [Nicolas Courty](http://people.irisa.fr/Nicolas.Courty/).


The slides of the Cours by Marco Cuturi can be downloadable [here](https://www.dropbox.com/s/3kuqnhmf2q0dzjq/mlss18_argentina.pdf?dl=0)   or
https://drive.google.com/file/d/1HCAI3E443PfF_sjoZgl8m24JF5nPJc9X/view


More information can be found in the [Computational Optimal Transport](https://arxiv.org/pdf/1803.00567.pdf) book.


You can download the introductory slides to the practical session [here](https://remi.flamary.com/cours/otml/OTML_TPDS3_2018.pdf).


optimal transport and machine learning
https://lchizat.github.io/files/presentations/chizat2019IFCAM_OT.pdf
https://mathematical-coffees.github.io/slides/mc01-courty.pdf
https://www.youtube.com/watch?v=mITml5ZpqM8
http://people.irisa.fr/Nicolas.Courty/OATMIL/


## some paper
Dolinsky, Y., Soner, H.M. Martingale optimal transport and robust hedging in continuous time. Probab. Theory Relat. Fields 160, 391–427 (2014). https://doi.org/10.1007/s00440-013-0531-y


May, A.D., Shepherd, S.P. & Timms, P.M. Optimal transport strategies for European cities. Transportation 27, 285–315 (2000). https://doi.org/10.1023/A:1005274015858


Galichon A. A survey of some recent applications of optimal transport methods to econometrics. Econometrics Journal. 2017;20(2):C1-C11. doi:10.1111/ectj.12083
