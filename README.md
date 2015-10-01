wktime
==============
This Plugin provides the capability to submit Time & Expense within redmine.

Install 
--------------

Get wktime

	# cd /usr/local/share/redmine/
	# git clone https://github.com/FCENG/redmine_wktime.git plugins/redmine_wktime

Install gem requirements

	# bundle install



Database migration

	# rake redmine:plugins:migrate NAME=redmine_wktime RAILS_ENV=production


Uninstall
--------------

	# rm -rf /usr/local/share/redmine/plugins/redmine_wktime
	# rake redmine:plugins:migrate NAME=redmine_wktime VERSION=0 RAILS_ENV=production


