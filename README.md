"# fhcampuskonfigmgmt" 


hab den push weder über die command konsole noch über git bash geschafft. folgende Fehlermeldung ist ständig gekommen: 

C:\Users\bernh\OneDrive\Desktop\Akademisch\Campus\Konfigurationsmanagement\PushUebung>git remote add origin https://github.com/bscampus/fhcampuskonfigmgmt.git
error: remote origin already exists.

C:\Users\bernh\OneDrive\Desktop\Akademisch\Campus\Konfigurationsmanagement\PushUebung>git push -u origin main
remote: Permission to bscampus/fhcampuskonfigmgmt.git denied to bscampus.
fatal: unable to access 'https://github.com/bscampus/fhcampuskonfigmgmt.git/': The requested URL returned error: 403

C:\Users\bernh\OneDrive\Desktop\Akademisch\Campus\Konfigurationsmanagement\PushUebung>git push --set-upstream origin master
error: src refspec master does not match any
error: failed to push some refs to 'https://github.com/bscampus/fhcampuskonfigmgmt.git'

C:\Users\bernh\OneDrive\Desktop\Akademisch\Campus\Konfigurationsmanagement\PushUebung>git remote add origin https://bscampus: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@github.com/bscampus/fhcampuskonfigmgmt.git
error: remote origin already exists.

C:\Users\bernh\OneDrive\Desktop\Akademisch\Campus\Konfigurationsmanagement\PushUebung>git push -u origin master
error: src refspec master does not match any
error: failed to push some refs to 'https://github.com/bscampus/fhcampuskonfigmgmt.git'

C:\Users\bernh\OneDrive\Desktop\Akademisch\Campus\Konfigurationsmanagement\PushUebung>
