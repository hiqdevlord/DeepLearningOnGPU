deep learning �����£�
*********************

Deep Learning Shape Priors for Object Segmentation
==================================================

��״���������ģ���˵������
modeling high-dimensional richly
structured data

deep learning Ϊʲô�ܽ�ģ��γ�����ݣ���


��������ʹ��deeplearning ������Щ��̫����ģ��Ͳ����������һЩ�������߲������������һЩ��������
The Shape-Time Random Field for Semantic Video Labeling
}
��������н�������shape time model���������������  ��ʱ�Ȳ�����


Switchable Deep Network for Pedestrian Detection
================================================

�����ʹ��deep������̽�⣬��һ���õ�һЩ�߲����Ϣ��������Щ�߲����Ϣ��ʲô�������ز����������֣��ǲ���һЩ������Ϣ��

Facial Expression Recognition via a Boosted Deep Belief Network
===============================================================

���ڵķ��඼�ǻ�������ѧϰ��


����ǲ�������ʹ�ö��DBN��Ȼ��ʹ�ö�������磬ʹ���������������о���

����������

.. math::

\xi_{strong}=\sum_{i=1}^{N_I}\beta_i[\frac{1}{1+\exp(-\sum)}-E_i]

����DBN���������ʲô��

ʹ�þ��������ѧϰlow-level feature��

��������е�switchָ����ʲô��

����㷨��ʹ�ò����沿ͼ�񣬱���nose��eye and mouth��

�㷨�������̣�

.. graphviz:

digraph G {
   edge [fontname="FangSong"];
node [shape=null, fontname="FangSong" size="20,20"];
{
a [label="ͼ��"];
b [label="����"  ];
c [label="������"];
d [label="��������"];

}

a->b   [label="1.ͼ��ֿ�"];
b->c    [label="2.ѧϰ�㼶������"];
c->b [label="3.���ݷ����γ�ǿ������"];
c->d [label="3.���ݷ����γ���������"];
}




���ʣ�
======

����ΪʲôҪ�������ʱ��ʹ���໥������patches�ǣ��������������Ǻܴ���

�㷨���µ㣺
===========

#. ��ǰ���㷨���ǻ�������ѧϰ������ѡ�񡢷���Լ����������������˳�����Ƕ����ģ�ȱ��ȫ�ַ������˷������γ���һ��ϵͳ��ʹ��ȫ��΢�����������������״̬��ֵ���������ŵ�ѧϰ


��չ�Ķ���
==========

#. On deep generative models with applications to recognition  
#. Disentangling factors of variation for facial expression recognition.

����������ʹ�ò㼶��������ʾ��logistic �ع齻���������Ŀ����࣬�����������ʹ�������������沿����ʶ��

#. Facial action unit recognition with sparse representation. 
#. Sparse coding for flexible, robust 3d facial-expression synthesis.
����ƪ����ʹ��sparse coding ��������������

���ܵĴ��µ㣺
==============

#.  ����㷨��ȫ��ʹ��ǿ����������������Ч���ǣ�


Switchable Deep Network for Pedestrian Detection
================================================

���������ʹ�����Ʋ������������ֳ��˵Ĳ�ͬ�顣�����������ֿ�ģ�

Pedestrian Parsing via Deep Decompositional Network
===================================================

�������������ʹ�õ���ʲô��


ȫ�ֵ�����ʲô��

Discriminative Deep Metric Learning for Face Verification in the Wild
=====================================================================

Mahalanobis Distance Metric Learning

��ͳ��Mahalanobis ������ͼ�ҵ������� :math:`M\in R^{d\times d}`
