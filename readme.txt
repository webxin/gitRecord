.git �汾��
git add �ļ���             ��ӣ����ļ��޸���ӵ��ݴ���
git rm  �ļ���             ɾ���ļ�
git commit -m ""           �ύ�����ݴ������������ύ����ǰ��֧

ʱ�⴩��
git log                    �鿴�ύ��ʷ����ȷ�����˰汾
git log --pretty=oneline   ��ʷ�汾��ʾΪһ��
git reflog                 �鿴������ʷ���Ա�ȷ��Ҫ��δ���汾

HEAD                       ��ʾ��ǰ�汾
git reset --hard �汾��    ���뵽ĳһ�汾

git�������汾����ϵͳ���� ���ݴ�������

.git                        �����ڹ���������git�İ汾��   


git status                  �鿴״̬
git diff  �ļ���            �鿴�仯
git checkout -- �ļ���      1.�޸ĺ�δ�ŵ��ݴ����������޸Ļص��Ͱ汾��һ��
		            2.������ݴ������������޸ģ�����������ݴ������״̬

git reset HEAD �ļ���       �ݴ������޸ĳ��������·Żع�����


git remote add origin git@github.com:yourname/learn.git
			    ���Զ�ֿ̲�	
			 			
git push -u master origin   �������͵�Զ�̣���һ���ύ��� -u
git clone                   ��¡Զ�ֿ̲�  

------------------------------------------------
��֧����


git branch                  �鿴���з�֧
git branch  dev             ����dev��֧
git branch -d  dev          ɾ��dev��֧
git checkout dev            �л���dev��֧ 

git checkout -b dev         �������л���dev��֧

git merge  dev              ���ٺϲ�ָ����֧����ǰ��֧��

git log --graph             ������֧��ͼ
Q����                       �˳�log�鿴

git merge --no-ff   dev     ��ͨģʽ�ϲ����ϲ�����ʷ�з�֧

git stash                   �ѹ��������£��޸�bug
git stash  pop              �ص������ֳ�

git branch -D dev           ǿ��ɾ��һ��û�кϲ��ķ�֧
 
git remote -v               ��ʾԶ�̿����Ϣ
			    ��ʾץȡ�����͵ĵ�ַ
git push origin dev         �Ѹ÷�֧���ύ���͵�Զ��


git branch  --set-upstream branch-name  origin/branch-name 
			    �����ط�֧��Զ�̷�֧������ϵ 
git pull                    ��ȡԶ�̷�֧

						
		
��ǩ����
git tag  v1.0   commit_id   ��֮ǰ�汾���ǩ
git tag  v1.0               ���ǩ
git tag                     �鿴���б�ǩ
git tag -a "��ǩ��" -m "˵������" 

git tag -d  "��ǩ��"        ɾ�����ر�ǩ
git push origin :refs/tags/<tagname> 
			    ɾ��Զ�̱�ǩ
git push origin  ��ǩ��     ����ǩ���͵�Զ��   
git push origin  --tag      ��ȫ����ǩ���͵�Զ��   


�Զ���git��
git bash �� ������touch .gitignore ���������ļ�

