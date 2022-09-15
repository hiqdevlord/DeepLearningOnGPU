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


��������н�������shape time model���������������  ��ʱ�Ȳ�����


Switchable Deep Network for Pedestrian Detection
================================================

�����ʹ��deep������̽�⣬��һ���õ�һЩ�߲����Ϣ��������Щ�߲����Ϣ��ʲô�������ز����������֣��ǲ���һЩ������Ϣ��


��չ�Ķ���
=========

Learning and selecting features jointly with point-wise gated Boltzmann machines

����������������з��࣬ǰ�������ͱ���������


Facial Expression Recognition via a Boosted Deep Belief Network
===============================================================

���ڵķ��඼�ǻ�������ѧϰ


����ǲ�������ʹ�ö��DBN��Ȼ��ʹ�ö�������磬ʹ���������������о���

L������ϸ����ܶȺ������Ա�ʾΪ��

.. math::

   \Prob(H^0,H^1,...,H^L)=\prod_{l=0}^{L-2}\Prob(H^l|H^{l-1})\Prob(H^{L-1},H^L)

:math:`\Prob(H^{l-1},H^l)` ��:math:`\Prob(H^{l},H^{l-1})` �ֱ��ʾΪ��

.. math::

   \Prob(H^{l-1}|H^l)=\frac{1}{1\exp((W^{l,l+1}H^l+b_h^{l+1}))}

����߲�ε����:mat:`H^L` ���Ա�ʾΪ��

.. math::

   H^L=  W^{L-1,L}H^{L-1}

����:math:`W^{L-1,L}H^{L-1}` �ǵ����ϲ��Ȩֵ����

�γ�����������

.. math::

   \xi_{strong}=\sum_{i=1}^{N_I}\beta_i[\frac{1}{1+\exp(-\sum\alpha j(Wj^(L1,L)H{i,j}^{L1}Tj) )}-E_i]^2

����:math:`\alpha` �� T���������������ޡ�ʹ���ݶ��½�����

ʹ�������ݶ��½�����

.. math::

   \xi\lamba\xi{strong}\xi{weak}


top ����ʹ��boosting �ṹ�� 0��L2��ʹ�� �������㷨��

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
   c [label="��������ǿ������������������"];

   }

   a->b   [label="1.ͼ��ֿ�"];
   b->c    [label="2.ѧϰ�㼶������"];
   c->b [label="3.���ݷ�������ǰ������"];
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


Hybrid Deep Learning for Face Verification
==========================================

��deep learning ��һֱ��ʹ�þ����������ȷ���ǣ���������������ʵ�����������ǲ������ˡ�

���ｨ������������������ʲô��˼��


��չ�Ķ���
==========

Deep convolutional network cascade for facial point detection  ʹ�þ����������̽����������


������¿��������ǷѾ���
 

DeepFace: Closing the Gap to Human-Level Performance in Face Verification
=========================================================================

ʹ����ά����ģ��ʹ��deep learning��


