# mbf
TOOLS  CURI  FB
import platform,os,sys
w = 'mhkbpcP'
	for i in w:
		j = w.index(i)
		x= x.replace('!%s'%i,'\033[%s;1m'%str(31+j))
	x += '\033[0m'
	x = x.replace('!0','\033[0m')
	if e != 0:
		sys.stdout.write(x)
	else:
		sys.stdout.write(x+'\n')
if platform.python_version().split('.')[0] != '2':
