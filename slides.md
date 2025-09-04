### Achievements and changes

#### Recent achievements (since the last meeting)

<small>

* From [resolved infra tasks](https://progress.opensuse.org/issues?set_filter=1&sort=priority%3Adesc%2Cid%3Adesc&f%5B%5D=status_id&op%5Bstatus_id%5D=%3D&v%5Bstatus_id%5D%5B%5D=3&f%5B%5D=fixed_version_id&op%5Bfixed_version_id%5D=%3D&v%5Bfixed_version_id%5D%5B%5D=418&f%5B%5D=closed_on&op%5Bclosed_on%5D=%3E%3D&v%5Bclosed_on%5D%5B%5D=2025-05-06&f%5B%5D=issue_tags&op%5Bissue_tags%5D=%3D&v%5Bissue_tags%5D%5B%5D=infra&f%5B%5D=&c%5B%5D=subject&c%5B%5D=project&c%5B%5D=priority&c%5B%5D=category&group_by=project&t%5B%5D=), 244 tickets since last report:
 * Support CC-compliance of PRG2 while ensuring business continuity [poo#165282](https://progress.opensuse.org/issues/165282)
 * Migration from racktables to netbox [poo#177537](https://progress.opensuse.org/issues/177537)
 * Proper ownership and maintainership for .qa.suse.cz and .qam.suse.cz [poo#154042](https://progress.opensuse.org/issues/154042)
 * The usual challenges with new machines as well as migrating machines
* Squad rotation by okurz, good success with stand-in nsinger

</small>

---

#### Important changes

<small>

* CC-compliance brought significant changes with two important factors:
 * The datacenters are used with strong reliance on PRG2 with no redundancy and NUE2 underused
 * QE engineers need to handle adaptations though full awareness is still missing -> risk of non-compliance
* From [monitor dashboard](https://monitor.qa.suse.de/):
 * Availability of OSD 94%, further significant decrease (!) mostly due to two
   incidents involving ill-configured bare-metal virtualization tests not sufficiently mitigated probably as
   could be expected from already communicated impediments

</small>

---

### Roadmap of the next period

<small>

Improve the openQA experience benefitting biggest user groups while staying compliant as well as performant:
* (old) Support switch to gitea for openSUSE/SUSE based products, e.g. SLE16 [poo#180626](https://progress.opensuse.org/issues/180626)
* Support SUSE PRG office move while ensuring business continuity [poo#168895](https://progress.opensuse.org/issues/168895)

See [QE tools team - backlog, top-level](https://progress.opensuse.org/issues?query_id=524) for reference

</small>

---

### Impediments and requirements

#### Impediments to the roadmap

<small>

* Same as last time: Growing requirements on OSD – more products, more versions, more tests, more users - are straining team resources

</small>


#### Resource requirements

<small>

* Infrastructure administration ressources: Team extension is getting more pressing especially considering availability and geo-redundancy (SLC1) requirements

See https://progress.opensuse.org/projects/openqav3/wiki/#openQA-infrastructure-needs-o3-osd
for reference

</small>

---

### Scope
* Recent achievements and changes (since the last meeting)
* Roadmap of the next period
* Impediments to the roadmap
* Resource requirements

---

### The end … Questions? Corrections? Additions?

<p><img src="img/chameleon.svg" style="max-height:300px;"></p>

<small>
Presentation created using <br><a href="https://github.com/krig/opensuse-presentation-template">https://github.com/krig/opensuse-presentation-template</a>
</small>

#### License
<small>
This slide deck is licensed under the Creative Commons Attribution-ShareAlike 4.0 International license.
It can be shared and adapted for any purpose (even commercially) as long as Attribution is given and any derivative work is distributed under the same license. Details can be found at <a href="https://creativecommons.org/licenses/by-sa/4.0/">https://creativecommons.org/licenses/by-sa/4.0/</a>
</small>
