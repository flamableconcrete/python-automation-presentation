# Python Automation Presentation

This is a presentation given by Jared Ondricek at the [NOVA-Python Meetup.com group][1]
on 10/27/2016.

The presentation covered the following three Python libraries:

* [Ansible](http://docs.ansible.com)
* [Supervisor](http://supervisord.org)
* [Fabric](http://www.fabfile.org)

[View the static presentation!][2]  
[View the live recording!][3]

In order to render the presentation, you will need to be using python 3 and
run the following command

```
pip install -r requirements.txt
```

This presentation was developed with the awesome [Hovercraft python library][4], which depends on Python 3.

To view the presentation in realtime while editing the presentation.rst file, just type:

```
hovercraft -a presentation
```

Or you can render this presentation to HTML with the command::

```
hovercraft presentation.rst outdir
```

And then view the outdir/index.html file to see how it turned out.

Here is a relatively easy way to present this in an offline manner,
such as for a conference presentation.

```
cd outdir
python3 -m http.server
```

Then going to 127.0.0.1:8000 in your browser. Enjoy!

[1]: https://www.meetup.com/NOVA-Python/events/234970214/
[2]: https://flamableconcrete.github.io/python-automation-presentation
[3]: https://em7.webex.com/em7/lsr.php?RCID=ac723ab78a614de28a45a091085bbd81
[4]: https://github.com/regebro/hovercraft
