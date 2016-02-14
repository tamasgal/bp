To keep an SSH connection alive (it mostly makes sense for an SSH tunnel for example) the best practise is to use `autossh`:

    autossh -M 20000 ...

where you replace `...` with your desired SSH command line arguments.

Source:
http://superuser.com/questions/37738/how-to-reliably-keep-an-ssh-tunnel-open
