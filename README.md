
<!---
pierreforstmann/pierreforstmann is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
```
$ dnf repolist pgdg15 -v
Loaded plugins: builddep, changelog, config-manager, copr, debug, debuginfo-install, download, generate_completion_cache, groups-manager, kpatch, needs-restarting, playground, repoclosure, repodiff, repograph, repomanage, reposync, system-upgrade
DNF version: 4.7.0
cachedir: /var/tmp/dnf-pierre-r_lqfk0d
Last metadata expiration check: 0:04:03 ago on Thu 03 Aug 2023 09:12:44 PM CEST.
Repo-id            : pgdg15
Repo-name          : PostgreSQL 15 for RHEL / Rocky 8 - x86_64
Repo-status        : enabled
Repo-revision      : 1690219827
Repo-updated       : Mon 24 Jul 2023 07:30:27 PM CEST
Repo-pkgs          : 428
Repo-available-pkgs: 428
Repo-size          : 309 M
Repo-baseurl       : https://download.postgresql.org/pub/repos/yum/15/redhat/rhel-8-x86_64
Repo-expire        : 172,800 second(s) (last: Thu 03 Aug 2023 09:12:32 PM CEST)
Repo-filename      : /etc/yum.repos.d/pgdg-redhat-all.repo
Total packages: 428

$ dnf info pg_readonly_15
Last metadata expiration check: 0:04:22 ago on Thu 03 Aug 2023 09:12:44 PM CEST.
Available Packages
Name         : pg_readonly_15
Version      : 1.0.3
Release      : 1.rhel8
Architecture : x86_64
Size         : 31 k
Source       : pg_readonly_15-1.0.3-1.rhel8.src.rpm
Repository   : pgdg15
Summary      : PostgreSQL extension which allows to set all cluster databases
             : read only.
URL          : https://github.com/pierreforstmann/pg_readonly
License      : PostgreSQL
Description  : pg_readonly is a PostgreSQL extension which allows to set all
             : cluster databases read only.
             : 
             : The read-only status is managed only in (shared) memory with a
             : global flag. SQL functions are provided to set the flag, to unset
             : the flag and to query the flag. The current version of the
             : extension does not allow to store the read-only status in a
             : permanent way.
```
