# what i did

I created the github repo in VS Code on windows 10

I synched it to github

I ran pip install on codespace

Now, I am waiting... the rasa package is huge and heavy...

No joy with rasa on codespaces either.

![image](https://user-images.githubusercontent.com/640846/203529572-329f9597-0e47-41ef-8385-6e1a642dc425.png)



# no joy with rasa on windows 10
## errors on install
Downloading jsonschema-3.2.0-py2.py3-none-any.whl (56 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 56.3/56.3 kB 731.2 kB/s eta 0:00:00Collecting mattermostwrapper<2.3,>=2.2
  Downloading mattermostwrapper-2.2.tar.gz (2.5 kB)
  Preparing metadata (setup.py) ... done
Collecting colorclass<2.3,>=2.2
  Downloading colorclass-2.2.2-py2.py3-none-any.whl (18 kB)
Collecting scikit-learn<0.23,>=0.22
  Downloading scikit-learn-0.22.2.post1.tar.gz (6.9 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 6.9/6.9 MB 1.5 MB/s eta 0:00:00    
  Preparing metadata (setup.py) ... done
Collecting gevent<1.6,>=1.4
  Downloading gevent-1.5.0.tar.gz (5.3 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 5.3/5.3 MB 1.6 MB/s eta 0:00:00    
  Installing build dependencies ... done
  Getting requirements to build wheel ... done
  Preparing metadata (pyproject.toml) ... done
Collecting psycopg2-binary<2.9.0,>=2.8.2
  Downloading psycopg2-binary-2.8.6.tar.gz (384 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 384.7/384.7 kB 1.7 MB/s eta 0:00:00  Preparing metadata (setup.py) ... error
  error: subprocess-exited-with-error

  × python setup.py egg_info did not run successfully.
  │ exit code: 1
  ╰─> [25 lines of output]
      C:\Users\denni\AppData\Local\Programs\Python\Python310\lib\site-packages\setuptools\config\setupcfg.py:463: SetuptoolsDeprecationWarning: The license_file parameter is deprecated, use license_files instead.
        warnings.warn(msg, warning_class)
      running egg_info
      creating C:\Users\denni\AppData\Local\Temp\pip-pip-egg-info-n_7l2tv9\psycopg2_binary.egg-info
      writing C:\Users\denni\AppData\Local\Temp\pip-pip-egg-info-n_7l2tv9\psycopg2_binary.egg-info\PKG-INFO
      writing dependency_links to C:\Users\denni\AppData\Local\Temp\pip-pip-egg-info-n_7l2tv9\psycopg2_binary.egg-info\dependency_links.txt
      writing top-level names to C:\Users\denni\AppData\Local\Temp\pip-pip-egg-info-n_7l2tv9\psycopg2_binary.egg-info\top_level.txt
      writing manifest file 'C:\Users\denni\AppData\Local\Temp\pip-pip-egg-info-n_7l2tv9\psycopg2_binary.egg-info\SOURCES.txt'
     
      Error: pg_config executable not found.
     
      pg_config is required to build psycopg2 from source.  Please add the directory
      containing pg_config to the $PATH or specify the full executable path with 
the
      option:
     
          python setup.py build_ext --pg-config /path/to/pg_config build ...     
     
      or with the pg_config option in 'setup.cfg'.
     
      If you prefer to avoid building psycopg2 from source, please install the PyPI
      'psycopg2-binary' package instead.
     
      For further information please check the 'doc/src/install.rst' file (also at
      <https://www.psycopg.org/docs/install.html>).
     
      [end of output]

  note: This error originates from a subprocess, and is likely not a problem with pip.
error: metadata-generation-failed

× Encountered error while generating package metadata.
╰─> See above for output.

note: This is an issue with the package mentioned above, not pip.
hint: See above for details.
