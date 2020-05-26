# dev_EmacsRH7
Many changes have been implemented for Emacs, specifically these updates are for RHEL 7.x

#### Add Yum Emacs

`$sudo yum install emacs`<br/>

#### Enable Snaps install of Emacs
***Add latest epel***<br/>
`$yum install https://dl.fedoraproject.org/pub/epel/epel-release-latest-7.noarch.rpm`<br/>
<br/>
`$yum install snapd`<br/>
<br/>
`$sudo systemctl enable --now snapd.socket`<br/>
<br/>
***enable classic snpa support, create following symlink***<br/>
`$sudo ln-s /var/lib/snapd/snap /snap`<br/>


