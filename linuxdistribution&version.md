import platform

print('Uname:', platform.uname())

print()
print('Distribution :', platform.linux_distribution())
print('Machine :', platform.machine())
print('Node :', platform.node())
print('Processor :', platform.processor())
print('Release :', platform.release())
print('System :', platform.system())
print('Version :', platform.version())
print('Platform :', platform.platform())
 
output:

Uname: uname_result(system='Linux', node='ostechnix', release='5.0.0-32-generic', version='#34~18.04.2-Ubuntu SMP Thu Oct 10 10:36:02 UTC 2019', machine='x86_64', processor='x86_64')

Distribution : ('Ubuntu', '18.04', 'bionic')
Machine : x86_64
Node : ostechnix
Processor : x86_64
Release : 5.0.0-32-generic
System : Linux
Version : #34~18.04.2-Ubuntu SMP Thu Oct 10 10:36:02 UTC 2019
Platform : Linux-5.0.0-32-generic-x86_64-with-Ubuntu-18.04-bionic
