Walker | Legged frame
===

<a href="http://github.com/worlddevelopment">worlddevelopment</a> mobile pivot.



Dependencies
---
see <a href="local.xml">local.xml</a>



Related modules
---
see <a href="http://wiki.opensourceecology.de/0install">0install</a>

* `walker_remote_control
* `walker_network_control`
* `hydraulic_manipulator



Reverse dependency examples
---
(none)



Functions | capabilities
---

<a href="simulation/templates/walker/capabilities.xml">simulation/templates/walker/capabilities.xml</a>

+
all those actions inherited from attached modules if its operation is known (e.g. illuminate, a capability of the lights)




Technologies used
---
(Required knowledge for construction, not operation! A knowledge can lead to many capability, object combinations|tuples.)
<a href="simulation/templates/walker/TechnologyRequired.xml">simulation/templates/walker/TechnologyRequired.xml</a>
Individuals (scientists, engineers, ...) have the knowledge, but a civilization only has the technology available for as long as there is this knowledge. So this might be called know-how.

Research task: How can we do this or that? -> Research in this direction using this theory, these experiments. Can we do it using existing tech already? If no then input time + effort. => Result: know-how (new effects (related or not) => new tech; or a solution using old tech; or a combination) or failure.



Technologies provided
---
Often this is invalid, because a machine can only have capabilities and not provide entire new technologies, unless it is a smart agent that researches new knowledge itself!
In 0BC terms this makes sense for being templates, e.g. Albert Einstein, providing knowledge:
<a href="simulation/data/techs/">simulation/data/techs</a>

''TODO: Outsource into JSON files to allow reuse in the <a href="http://github.com/worlddevelopment/virtual_time_machine">Virtual Time Machine</a>. A new technology can lead to new capabilities of things, thus beings. Thus this struct here may require some technology (set of capabilities) to be constructed.''
It's hierarchical: (another reason for the TODO above)

* Electricity (battery recharge interface, electrical cooperation)
* Mechanics (frame, coupling, ...)
  * Hydraulics (schema exported from mechanics)

=> A tech tree guides the program to have citizens find something new. (without the program actually being required to do real research -- is there a program doing active research already?)

When a citizen find it, then the tech is activated, i.e. new structs can be built, the knowledge is still limited to the research group or rather where the information is stored (includes the brain, papers of the researchers).

This is especially about structures which can not learn actively itself. These must have its capabilities clearly specified or the functionality is added via e.g. new attachments with specified new features due to the technology research become available and the tank can be upgraded.



Links
---
* Manual (not available)

