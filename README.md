<code>
newcpan &lt;category&gt; &lt;packagename&gt; &lt;rev&gt; - create a trivial perl port for twea
   e.g.
newcpan devel IO::Async 0.61
   - asks for MAINTAINER line once, stores result in $HOME/.newcpanrc
   - asks for COMMENT line (can we auto retrieve from cpan somehow?)
   - creates /usr/ports/openbsd-wip/devel/p5-IO-Async/Makefile
   - attempts to 'make makesum'
   - attempts to 'make plist'
   - bails if anything fails along the way
</code>
