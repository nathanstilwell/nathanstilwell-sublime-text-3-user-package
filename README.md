# My Sublime Text User

This is a central place for me to keep my Sublime Text User settings. Make sure you install [Package Control](http://wbond.net/sublime_packages/package_control/installation) first by dumping this:

    import urllib2,os; pf='Package Control.sublime-package'; ipp=sublime.installed_packages_path(); os.makedirs(ipp) if not os.path.exists(ipp) else None; urllib2.install_opener(urllib2.build_opener(urllib2.ProxyHandler())); open(os.path.join(ipp,pf),'wb').write(urllib2.urlopen('http://sublime.wbond.net/'+pf.replace(' ','%20')).read()); print 'Please restart Sublime Text to finish installation'

into the SublimeText console (by hitting *ctrl + `*)
