# PAFL

Due to the wide coverage area and long imaging distance of remote sensing (RS) technology, the nonuniform thickness of haze during the imaging process often leads to interference from the nonuniform haze in RS images. Currently, most dehazing methods only aim to address homogeneous hazy RS images and cannot effectively remove nonuniform haze in RS images. To deal with this problem, we propose a novel physical-guided attentive feedback learning (PAFL) model, which is used to restore ground objects under nonuniform haze conditions. Firstly, we establish a new nonuniform haze model for RS images to reveal the degradation process of nonuniform hazy RS images from the perspective of physical imaging. Based on the new nonuniform haze model, a physical model-based dual-layer decomposition network is proposed, which combines unsupervised prior guidance information to learn haze layer and scene layer features from nonuniform hazy RS images. Secondly, a dual-layer guided multi-scale attention feedback network (DL-MSAFN) is designed, which uses the haze layer and scene layer as auxiliary information to guide the network to efficiently learn the distribution features of nonuniform haze. Finally, we propose attentive feedback blocks (AFBs) in the DL-MSAFN to generate clearer dehazing results through a self-correcting feedback mode. To this end, we also develop a synthetic RS dataset with nonuniform haze, which can alleviate the dilemma of hazy RS datasets. Experimental results on several nonuniform hazy RS datasets and real hazy RS images show that the proposed PAFL model is superior to the compared algorithms in both qualitative and quantitative evaluations.

# Key words

Dehazing, remote sensing, nonuniform haze, attentive feedback learning 

# Code

The code will be available after this paper is accepted.
