# Welcome to Telecom ParisTech

This is a list of things you should know it exists.

Please [edit this page](https://github.com/TomDLT/TPT/edit/master/README.md) if you have useful links or scripts to share.

## TPT administration
- [Eole](https://eole.telecom-paristech.fr/accueil.php): TPT intranet (_in french_)
    - You can book a meeting room, find paperwork for travelling to conferences, ...
- [Zimbra](https://z.mines-telecom.fr/zimbra/mail): TPT webmail
- [Min&Tel](https://mintel.imt.fr): another TPT intranet (_in french_)
    - This is where you can declare your holidays.
- [TPT](https://www.telecom-paristech.fr/eng): TPT public website
    - You can find some informations about accomodation, healthcare, cost of living, ...
- [IDS](https://intranet.tsi.telecom-paristech.fr/): IDS department intranet (_in french_)

## TPT account
- [Your account](https://moncompte.telecom-paristech.fr//mon_compte/): Some information about your TPT account (_in french_)
    - You can change your passwoprd, set up wifi connexions for guests, ...
- [DSI](https://www.telecom-paristech.fr/vivre-ecole/services-numeriques-dsi.html): Many information about the services of the DSI (the IT department) (_in french_)
- [SOS](https://sos.telecom-paristech.fr/front/helpdesk.public.php): You can ask any question to the DSI about your account, your desktop, the wifi, ... 
- Personal website: The DSI can host your personal website at `https://perso.telecom-paristech.fr/your_login`. Activate it from [your account](https://moncompte.telecom-paristech.fr//mon_compte/), and store the files in `~/public_html`.
    - GitHub can also [host](https://pages.github.com/) your personal website at `https://your_github_login.github.io/`
- Home: Your home directory is accessible from most machines in TPT, but its size is limited to ~8 Gbytes
- More space: You can ask the DSI for more space on your local desktop, or on a shared directory in `/tsi/doctorants/your_login`
- [Wifi connection](https://www.telecom-paristech.fr/vivre-ecole/services-numeriques-dsi/connexion-au-reseau-sans-fil.html): To setup wifi in TPT (_in french_)
    - You can also use your email address (`name.surname@telecom-paristech.fr`) and your TPT password to connect to the `eduroam` wifi, available in most french universities.

## TPT ssh and clusters
- SSH:
    - To access TPT by SSH from outside TPT, use `ssh your_login@ssh.enst.fr`; you are now inside.
    - To access a specific machine, e.g. lame10, use `ssh your_login@lame10`. Note that you need to be inside TPT.
    - To do both step in one, you can easily [redirect](https://superuser.com/a/170592/601170) your ssh (_Linux_).
- [Infres cluster](https://services.infres.enst.fr/cpu/): A list of powerful machines you can access by ssh, without any queuing system.
    - lame10-16: You have your home folder unchanged, so it's very easy to use.
    - lame17-19: You need to install what you need, your home is not accessible.
    - lame20-22: You can book these machines on [this wesite](https://reservation.r2.enst.fr/app/Web/view-schedule.php).
    - If you need the gpu, or if you need help with these machines, ask nicolas.bouche@imt.fr
- [IDS cluster](http://www.cluster.enst.fr/): A cluster you can access by ssh, but you need to use the queue.
    - Please read the doc before using it ! (_in french_)
- [TP rooms](https://www.telecom-paristech.fr/vivre-ecole/services-numeriques-dsi/salles-de-tp/equipements.html): list of desktops available from 8.00 AM to 11.59 PM, if not in used by students.
- [IDS desktops](https://intranet.tsi.telecom-paristech.fr/pcs_linux/stations/stations.html):  list of desktops of the departement IDS
- [VPN](http://www.telecom-paristech.fr/fileadmin/documents/images/Vivre_ecole/services_numeriques/Documentation/PPTP_Linux.pdf) for accessing scientific papers from outside Telecom ParisTech ... legally. Or if you want to pretend you are in France when you are in India.

## Working tools
- [Git](https://git-scm.com/): Must-have version control tool
    - [Tutorial](https://git-scm.com/docs/gittutorial), [Cheat-sheet](https://www.git-tower.com/blog/git-cheat-sheet/), [Development workflow](https://docs.scipy.org/doc/numpy/dev/gitwash/development_workflow.html)
- [GitHub](https://github.com/): Host your git repositories online. 
    - As a student/academic, you can ask for a [free developer plan](https://education.github.com/pack), to have unlimited private repos.
    - Alternatively, you can use [GitLab](https://gitlab.telecom-paristech.fr/users/sign_in), hosted by TPT (you need to raise a [sos ticket](https://sos.telecom-paristech.fr/front/helpdesk.public.php) to create a project)
- [Linux commands](https://github.com/jlevy/the-art-of-command-line/blob/master/README.md): Selection of notes and tips on using the command-line.
    - [Shell command explained](https://explainshell.com/)
- [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh): Customize your shell to have colors, current git branch, current environnement, ...

## Python tools
- [Anaconda](https://www.continuum.io/downloads): A good way to have everything you need for python
    - [Miniconda](https://conda.io/miniconda.html): To have the conda package manager, but not all the default packages of Anaconda
- [Windows binaries](http://www.lfd.uci.edu/~gohlke/pythonlibs/): Packages compiled for Windows (unofficial).
- Scientific basic packages: ipython, numpy, scipy, pandas, jupyter, matplotlib
    - [Cheat-sheet](https://ipgp.github.io/scientific_python_cheat_sheet/), [Scipy lectures](http://www.scipy-lectures.org/), [Numpy for Matlab users](http://scipy.github.io/old-wiki/pages/NumPy_for_Matlab_Users)
- Editing tools: pep8, flake8, yapf
- Profiling: snakeviz, line-profiler, memory-profiler
- Editors: sublime_text/atom, spyder/pycharm (Matlab style)
- Awesomeness: [list of links](https://github.com/kirang89/pycrumbs)

## Matlab
- Please [edit this page](https://github.com/TomDLT/TPT/edit/master/README.md) if you have useful links to share, or tips to use Matlab in TPT.

## Research tools
- [Sci-Hub](http://sci-hub.cc/): Free access to most scientific papers
- [Libgen](http://gen.lib.rus.ec/): Free access to most scientific books

## LaTeX tools
- [Detexify](http://detexify.kirelabs.org/classify.html): Find the LaTeX command for a rare symbol, from drawing
- [Table generator](http://www.tablesgenerator.com/): Online tool to build tables in LaTeX
