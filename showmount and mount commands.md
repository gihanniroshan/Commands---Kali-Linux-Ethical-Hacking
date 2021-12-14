## showmount command usage
```
showmount -e 10.2.2.2 
```
`-e` or `--exports` shows the export list

**output**
<pre>
/share        (everyone)
/my-notes     (noone)
</pre>


## mount command usage
```
mount 10.2.2.2:/share fold1
```

"share" is shared folder in the host and  
 "fold1" is on our machine.  
 Simply saving a copy of 'share' folder in to our local machine's 'fold1'
 
 **output**  
 Go to the 'fold1' to see the output!
