Recently, I had the opportunity to test Microsoft Defender External Attack Surface Management (EASM) and explore how it can help security teams identify and manage an organisation's internet-facing attack surface.

One of my key takeaways was simple:

You can't protect an asset if you don't know it exists.

I started by testing the Discovery capability and configuring known assets as Discovery Seeds.

These can include:

🔹 Domains
🔹 Hosts
🔹 Public IP ranges
🔹 ASNs
🔹 WHOIS organisations
🔹 Email contacts

From those initial seeds, Defender EASM recursively maps relationships to discover additional internet-facing infrastructure associated with the organisation.

What interested me most was seeing how this changes the security perspective.

Instead of asking:

“What assets do we have in our CMDB?”

EASM encourages us to ask:

“What assets can an attacker discover about us from the Internet?”

During my testing, I explored how discovered assets are brought into the EASM inventory and classified based on their relationship to the organisation:

Approved Inventory | Dependency | Monitor Only | Candidate | Requires Investigation

This classification is particularly useful because not every discovered asset should automatically be considered organisation-owned. Candidate and investigation-required assets can be reviewed to validate ownership and relevance.

From a Security Operations and Vulnerability Management perspective, I see significant value here.

A traditional vulnerability scanner may be very effective against assets we already know about.

But EASM helps address a different problem:

Unknown Asset → Unmanaged Exposure → Unpatched Vulnerability → Potential Attack Path

This becomes increasingly important with cloud adoption, Shadow IT, acquisitions, third-party infrastructure and rapidly changing internet-facing services.

Microsoft also continuously refreshes asset information, helping organisations maintain a more current view of a changing external attack surface rather than treating asset discovery as a one-off exercise.

For me, testing EASM reinforced an important security principle:

Asset Discovery → Exposure Visibility → Vulnerability Identification → Risk Prioritisation → Remediation

EASM isn't simply about finding more assets.

It's about understanding what your organisation looks like to an attacker before the attacker takes advantage of something you didn't know was there.

That external perspective can be extremely valuable when combined with Vulnerability Management, SOC operations, Threat Intelligence and Incident Response.

Know your assets. Understand your exposure. Reduce your attack surface.

#CyberSecurity #MicrosoftDefender #EASM #AttackSurfaceManagement #SecurityEngineering #VulnerabilityManagement #SecurityOperations #SOC #ThreatManagement #ThreatIntelligence #CloudSecurity #ShadowIT #MicrosoftSecurity #CyberRisk
