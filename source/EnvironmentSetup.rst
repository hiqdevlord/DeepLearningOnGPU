Linux������׼��
===============

��Ҫ�Ǹ��� `caffe install manual <http://caffe.berkeleyvision.org/installation.html>`_ �����еġ���Ҫ���������������� https://github.com/gwli/StudyNote/blob/master/caffe/install/prepare.py ����ɰ�װ��

nvidia dridver �İ�װ 
---------------------

#. �� `����<http://www.nvidia.com/Download/index.aspx?lang=en-us>`_ ��������driver, 

#. �����ַ�����  tty1
   
   :command:`ctl+alt+F1` 

#. �ص� X windows.

   :command:`sudo service lightdm stop`

#. ��װdriver.

   :command:`chmod +x installer.run;./installer.run`


#. �ָ� X windows.
    
   :command:`sudo service lightdm start`


.. note:: 

   �����������installer���Զ�disable���Դ���driver,���ʧ�ܵ�����һ�£�����ִ��installer�����ˡ�

��װcuda-toolkit
----------------

��������ַ�ʽ����װ���ֶ���װ������ʹ�� `jetpack pro <http://developer.download.nvidia.com/embedded/jetson/TK1/docs/2_GetStart/Jeston_TK1_QuickStartGuide.pdf#nameddest=Flashing%20Jetson>`_ ֻ��װ host�˵�cuda-toolkit.

#. ���Դ

   .. code-block:: sh

      $ dpkg -i cuda-repo-ubuntu1404_6.5_amd64.deb

#. ��װcuda toolkit

   .. code-block:: sh

      $ sudo apt-get install -y cuda-toolkit-6-5

#. ���ƻ�������
   
   .. code-block:: sh

      $ export PATH+=/usr/local/cuda-6.5/bin/:
      $ LD_LABRARY_PATH+= /usr/local/cuda-6.5/bin/lib:


