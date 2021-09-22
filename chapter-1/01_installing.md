# Getting the stuff

*Where should we Go?*

Ok, so you've decided that you you'd like to write and run some Go code. GOOD!

Now we just need to get it.

In Java world, there are currently multiple distributions of a development kit. Do you want a Java from Oracle, Amazon,RedHat or Microsoft? Or perhaps from Zulu or AdoptOpenJDK(Adoptium)? Choose wisely, depending on the runtime environment and licence conditions. Then you got multiple versions. There is a latest version, LTS (Long-term-support) version, some obsolete LTS versions, that people still use. Plus you can choose which JVM you want to run - are you a HotSpot or OpenJ9 guy?

I know, I'm kinda exaggerating right now. In most cases you pick your favorite one or you are told by your superiors in your work. And when you really don't know which one to choose, you just go for the latest AdoptOpenJDK(Adoptium) build.

Well, good news. You do not have to worry about this decision in the Go world.

Just go to https://golang.org/dl/ and download the latest Go for your platform.

Installation is not complicated, as you can see on the Go install instructions: https://golang.org/doc/install - either run an installer or just extract a package and update the PATH variable.

Go authors are really careful about backward compatibility. Meaning, that code that is written for older version of Go runtime will run on the newer one. So you can find some archaic libs and apps that are still functional.

