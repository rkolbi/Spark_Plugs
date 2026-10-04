# Spark-Plug Gaps, Electrode Design & Selection Beyond the OEM Part Number

## Gap, Electrode Design, Firing Voltage, and Why the Rest of the Ignition System Matters

### Key takeaways

- **Gap:** Moving from .060 to about .040 inch cuts the modeled firing-voltage requirement by roughly a quarter, leaving more reserve for an aging crab-cap secondary system. The same percentage saving is worth more actual volts during heavy loads and hard acceleration, when firing-voltage demand is highest.
- **Electrode design:** A fine-wire tip concentrates the electric field about 2.4 times more strongly than a conventional large electrode. In the model, that translates to roughly 12–24% less firing voltage at the same gap.
- **Reserve and durability:** In the calculated model, a system with 25% reserve over a regular .060-inch plug's heavy-load needs can lose about 20% of its available voltage before misfiring. With a regular .040-inch plug it can lose about 39%, and with the IT16TT about 51%. Each extra .005 inch of gap wear adds roughly 9–11% to a regular plug's demand, which is why holding the gap and tip shape matters.
- **GM precedent:** GM TSB #03-06-04-060B documents GM moving a number of later V8s to an iridium-tip plug with a factory .040-inch gap, and it attributes the smaller gap to the different firing-tip design. It does not cover the L29, but it shows GM itself pairing a fine-wire tip with a tighter gap instead of treating .060 inch as a given.
- **L29 factory-spec discrepancy:** The *1997 Chevrolet Light Duty CK Truck Service Manual, Volume 1-1* contains conflicting spark-plug-gap specifications for the L29 7.4L. The engine-mechanical specifications list .035 inch, while the ignition-system specifications list .060 inch. That inconsistency is another reason I do not think .060 inch should automatically be treated as the only meaningful reference point when considering plug design and ignition-system demand.
- **Limits:** All of these numbers are calculated estimates, not measured L29 data. A lower-demand plug cannot fix a worn cap, rotor, or wires, or problems like fuel delivery, and it only makes sense if the plug is otherwise correct for the engine, including thread, reach, seat, heat range, and firing-end protrusion.

### Bottom line up front

On the L29, moving from the .060-inch plug gap listed in the ignition-system specifications to something around .040 inch will reduce the voltage the secondary ignition system has to develop before the spark jumps the gap, and may help the engine maintain more consistent ignition performance under load, where cylinder pressure drives firing-voltage demand higher. Requiring less voltage leaves more secondary-ignition reserve through the coil, distributor cap, rotor, plug wires, and insulation, and reduces the chance that age, moisture, carbon tracking, or other weaknesses become the easier electrical path. It can also help preserve reliable spark performance under load rather than spending so much of the system's available voltage margin just getting across the plug gap.

That general direction is also interesting in light of GM TSB #03-06-04-060B, which documents GM's move on a number of later V8 applications from platinum plugs to a newer iridium-tip plug manufactured with a .040-inch gap. The bulletin specifically attributes the gap change to the different firing-tip design. It does not apply directly to the L29, but it provides a useful GM example of how a change in electrode design can accompany a substantially smaller specified gap.

A newer fine-wire plug can potentially improve that situation further. Something like the Denso IT16TT combines a ~.040-inch gap with a 0.4 mm iridium center electrode and a 0.7 mm platinum ground electrode — the opposed fine-wire electrode design Denso markets as "Twin-Tip." The fine firing geometry typically requires somewhat less voltage than a conventional large-electrode plug at the same gap, while the precious-metal construction helps preserve that geometry and gap over time. In the like-for-like model described later in this article, the IT16TT's modeled firing-voltage requirement comes out roughly 12–24% lower than a conventional plug at the same gap, and roughly 33–42% lower than a conventional .060-inch plug. The same model suggests the tighter gap and fine tip also let the ignition system absorb more aging before it misfires, and that the fine electrodes leave much less metal around the developing flame kernel (a geometric estimate only). Those are calculated estimates, not measured L29 data.

So the attraction for me is not horsepower or a "magic" spark plug. It is the combination of a more moderate gap and a modern fine-wire design that should give the engine a good, durable spark while asking less from the rest of the secondary ignition system. That does not mean .060 inch cannot work, or that everyone should run the same plug. A fresh, healthy ignition system typically handles the wider gap just fine. My interest is in preserving more ignition margin, helping maintain stronger and more consistent ignition performance under heavy load, and reducing unnecessary secondary-system stress — particularly on an L29 still using the Vortec crab-cap distributor.

![Grouped bar chart of estimated spark voltage needed under light and heavy load: a regular .060 inch plug is the 100 percent baseline at light load and about 190 percent under heavy load; a regular plug at .040 inch needs about 76 and 144 percent; the Denso IT16TT at .040 inch needs about 63 and 116 percent](modeled-voltage-reduction.png)

*Estimated spark voltage needed, relative to a regular .060" plug at light load. Calculated model results, not measured L29 data. Details below.*

What started out as me comparing two spark plugs turned into a much deeper look at how spark-plug gap, electrode design, cylinder pressure, temperature, and the condition of the ignition system all work together. The L29 7.4L Vortec is an especially interesting engine to look at because the factory information itself raises questions. In the 1997 service manual, the engine-mechanical specifications list a .035-inch spark-plug gap, while the ignition-system specifications later list .060 inch. That discrepancy is what originally sent me down this rabbit hole.

![97 Chevrolet Light Duty CK Truck SM-Volume 1-1, Engine Mechanical Specifications](conflicting-gaps-1.png)



![97 Chevrolet Light Duty CK Truck SM-Volume 1-1, Ignition System specifications for Spark Plugs](conflicting-gaps-2.png)

*1997 Chevrolet Light Duty CK Truck Service Manual, Volume 1-1. The engine-mechanical specifications list **0.035 in.**, while the ignition-system specifications list **0.060 in.** The latter is printed as “0.60,” which I assume means 0.060 in., not 0.600 in.*

I first looked at the ACDelco R44LTS as a conventional tighter-gap alternative. Then I came across the Denso IT16TT, which is already configured around a ~.040-inch gap and uses manufacturer-stated 0.4 mm iridium center and 0.7 mm platinum ground electrodes. The R44LTS represents the conventional large-electrode plug design commonly associated with the tighter-gap approach on these engines, while the IT16TT uses a much finer iridium/platinum electrode design that became far more common in later production spark plugs. At that point, the question became less about brands and more about what the plug is actually asking the ignition system to do.

Before going further, I also wanted to make sure I was comparing plugs with appropriate basic fitment. The R44LTS uses a 14 mm thread, 17.5 mm reach, tapered seat, and 5/8-inch hex (about 15.9 mm). Denso lists the IT16TT with the same 14 mm thread, 17.5 mm reach, and tapered seat, but with a nominal 16 mm hex, which is essentially the same size as the R44LTS's 5/8-inch hex.

Heat-range numbers themselves cannot be directly compared between brands because each manufacturer uses its own scale, so I relied on manufacturer cross-reference information rather than trying to translate the numbers literally. Denso's own cross-reference maps the R44LTS to the IT16 family. Cross-reference information is still a reference rather than an absolute application guarantee, but it gave me a much better basis for the comparison than simply matching numbers printed on the plugs.

## Gap Is Only Part of the Story

A wider spark-plug gap can offer combustion benefits, but wider is not automatically better. Increasing the gap exposes more of the air/fuel mixture to the initial discharge and can help the developing flame kernel establish itself, improving combustion stability and, under some conditions, slightly increasing engine output. There is an optimum gap, however, because firing-voltage demand rises as the gap increases. Once the gap becomes too large for the ignition system to fire reliably under the engine's most demanding conditions, misfires begin and any potential combustion advantage is lost. During hard acceleration, towing, or climbing a grade, higher cylinder pressure and mixture density make that limit especially important. The practical goal is therefore not the widest possible gap, but the widest gap that provides a useful combustion benefit while still leaving adequate ignition-system reserve.

I put together a simple comparison showing how the voltage needed to fire a conventional plug changes with gap size under representative light-load and heavy-load conditions. I also included the IT16TT at its ~.040-inch gap using the separate calculated fine-wire adjustment discussed below, just to show where it might fall relative to the conventional plugs.

For the comparison, I used representative pre-spark conditions of about 5 bar absolute / 600 K for the light-load case and 13 bar / 720 K for the heavier-load case. Those are representative operating points, not measured L29 cylinder-pressure or temperature data. The purpose of the calculation is to compare trends as gap and load change, not to predict the exact firing voltage of my engine. The conventional rows use a standard empirical formula for the breakdown voltage of air, which accounts for gap, pressure, and temperature. The step-by-step calculation is in Appendix A at the end of this article.

| Plug / Gap          | Light Load | Heavy Load | Light Load, % of .035 LL | Heavy Load, % of .035 LL |
| ------------------- | ---------- | ---------- | ------------------------ | ------------------------ |
| Conventional .035"  | ~8.0 kV    | ~15.4 kV   | 100%                     | 192%                     |
| Denso IT16TT ~.040" | ~7.4 kV    | ~15.0 kV   | 92%                      | 187%                     |
| Conventional .040"  | ~8.9 kV    | ~17.3 kV   | 112%                     | 216%                     |
| Conventional .045"  | ~9.9 kV    | ~19.2 kV   | 123%                     | 239%                     |
| Conventional .050"  | ~10.8 kV   | ~21.0 kV   | 135%                     | 263%                     |
| Conventional .055"  | ~11.7 kV   | ~22.9 kV   | 146%                     | 286%                     |
| Conventional .060"  | ~12.6 kV   | ~24.7 kV   | 157%                     | 309%                     |

*Note: The last two columns show each value as a percentage of the conventional .035-inch light-load (LL) value. For example, 309% means 3.09 times the baseline, which is a 209% increase over that baseline. The percentages are calculated from unrounded values, so they can differ by a point from what the rounded kilovolts shown here would give.*

*The IT16TT values are calculated estimates only. There is no measured L29 data behind that row, and the fine-wire correction is intended only to demonstrate the modeled and approximate scale of the electrode-geometry effect, not to predict an actual firing voltage. The physical reasoning behind that adjustment, and a cross-check of it using a consistent geometry model, is worked through in the "Electrode Design Matters Too" section below.*

![Modeled firing-voltage requirement versus plug gap for a conventional plug under light and heavy load, with the Denso IT16TT shown at about .040 inch](firing-voltage-vs-gap.png)

*Modeled firing-voltage requirement versus gap, from the table above. The stars show the IT16TT at about .040 inch under the same two load conditions.*

The IT16TT row is different from the others. The conventional rows are based on gap, pressure, and temperature alone, while the Denso row uses a modeled effective-gap reduction to approximate the lower breakdown demand expected from its fine firing geometry (the effective gaps are worked out in Appendix A). I did not simply subtract a fixed percentage from the conventional .040-inch result. Because the underlying breakdown relationship is nonlinear, the apparent percentage reduction changes with operating conditions. That is why the estimated IT16TT value is about 17% below the conventional .040-inch value in the light-load example but only about 13% lower in the heavier-load example. The row is therefore an illustration of the expected direction and approximate scale of the effect, not a measured L29 result.

Looking at conventional plugs under the same operating condition, going from .035 inch to .060 inch raises the modeled breakdown requirement by roughly 57–60%. Looking across the broader operating range, the comparison goes from about 8.0 kV for .035 inch under the representative light-load condition to about 24.7 kV for .060 inch under the heavier-load condition — roughly a 209% increase, or about 3.1 times the voltage.

Those numbers were never intended to represent measured L29 firing voltages; the useful part is the trend. The comparison shows two things happening independently and together: increasing the gap raises the required voltage, and increasing cylinder pressure under load raises it again. The simple comparison also does not account for the detailed effects of electrode shape except for the separate calculated adjustment applied to the Denso row.

This is where Road Trip's experience with a Sun 1115 engine analyzer really helped connect the theory to the real world. He described watching firing voltage climb quickly during a snap-throttle test and then settle back down once the engine reached a steady rpm. He also remembered marginal ignition systems that behaved perfectly well at idle and light throttle but could lose the spark once cylinder pressure increased. That is pretty much the physics showing up on a shop scope. His firsthand experience was one of the things that helped me frame the discussion around ignition reserve rather than just plug gap by itself.

## Why This Becomes Important on the L29

Before the plug fires, the ignition system has to develop enough secondary voltage for the gap to break down. That secondary circuit includes the coil secondary, coil wire, distributor cap, rotor, plug wire, and spark plug. Ideally, the first electrical breakdown happens exactly where we want it: across the spark-plug gap.

As required firing voltage rises, however, so does the opportunity for that voltage to find another path through moisture, carbon tracking, cracked insulation, a worn cap or rotor, or a weak plug wire. That matters on the L29 because the Vortec crab-cap distributor has a long history of reported cap and rotor durability problems.

The broader GMT400 owner experience also seems to show a recurring preference for somewhat tighter gaps on distributor-equipped Vortec engines. Around .040–.045 inch repeatedly comes up as a commonly successful range, particularly on the L29. Some owners report smoother operation or fewer heavy-load ignition problems after moving away from .060 inch.

That does not mean .060 inch cannot work. A fresh, healthy ignition system may handle it just fine. I think the more useful way to look at it is that the larger gap spends more of the available secondary-voltage reserve. A somewhat tighter gap simply leaves more margin for heavy cylinder pressure, aging parts, moisture, and wear.

And of course, a lower-demand spark plug will not fix a bad ignition system. If the cap is tracking, the rotor is worn, or the plug wires are leaking, those problems still need to be corrected.

### A Relevant GM Iridium-Gap Change

GM TSB #03-06-04-060B, "Information on New Spark Plugs and Gapping," documents a later GM transition from platinum plugs to the ACDelco 41-985 iridium plug on a number of 4.8L, 5.3L, 5.7L LS1/LS6, and 6.0L applications.

The new plug was manufactured with a .040-inch (1.01 mm) gap, and GM instructed technicians not to alter that factory-set gap. The bulletin specifically states that the gap changed because of the different iridium firing-tip design.

The important limitation is that this bulletin does not include the L29 7.4L, L30 5.0L, or L31 5.7L Vortec engines, so I would not treat it as a direct gap specification for those engines.

I still think it is relevant to this discussion because it provides a useful GM example of a substantially smaller plug gap being adopted alongside a change in firing-end design. It also reinforces the broader point that electrode geometry and gap have to be considered together rather than treating .060 inch as universally desirable regardless of the plug being used.

## Electrode Design Matters Too

Two plugs with the same measured gap do not necessarily place the same demand on the ignition system. A conventional plug typically uses a comparatively large center electrode and a wide ground strap, while the IT16TT uses manufacturer-stated 0.4 mm iridium center and 0.7 mm platinum ground electrodes.

![Denso TT electrode vs ACDelco traditional electrode](electrode-design.png)

Gas breakdown is often discussed in Paschen-like terms because pressure, temperature, and gap distance strongly influence the voltage required to initiate a discharge. Electrode geometry adds another layer to that picture. A very small-radius firing tip concentrates the local electric field much more strongly than a broad conventional electrode, so the gas immediately around that tip can reach the conditions needed for breakdown at a somewhat lower applied voltage. That is the physical basis for expecting a fine-wire plug to require less firing voltage than a larger-electrode plug at the same nominal gap.

### Putting a Number on Field Concentration

To get a feel for how big the geometry effect could be, I started with a standard point-to-plane approximation for the peak electric field at a sharp tip, which depends on the tip radius, the gap, and the applied voltage. That shortcut is least accurate when the gap is close to the tip radius, so I also solved the same geometry exactly. At a .040-inch gap (1.016 mm), I compared a conventional ~2.5 mm center electrode (tip radius about 1.25 mm) against the IT16TT's 0.4 mm iridium center electrode (tip radius about 0.2 mm). The formulas and worked steps are in Appendix B. The results, per volt applied, were:

| Electrode | Tip radius r | Rough formula (per volt) | Exact solution (per volt) | Relative to conventional |
|---|---|---|---|---|
| Conventional (~2.5 mm center) | 1.25 mm | ~1.4 mm⁻¹ | ~1.5 mm⁻¹ | 1.0× |
| IT16TT iridium (0.4 mm center) | 0.2 mm | ~3.3 mm⁻¹ | ~3.5 mm⁻¹ | ~2.4× |

![Bar chart comparing the peak tip electric field per volt for a conventional plug and the Denso IT16TT, using the rough formula and the exact solution](field-concentration-comparison.png)

*Peak tip field per volt applied at a .040-inch gap, from the table above.*

In practical terms, 10 kV across the gap would produce a peak tip field of roughly 15 kV/mm on the conventional plug and 35 kV/mm on the fine-wire plug. The fine tip reaches a given field strength at a much lower applied voltage.

**This is not a prediction that the IT16TT needs 2.4 times less voltage.** Breakdown in a running engine depends on how the field is distributed across the whole gap, not just on the peak at the tip, and on cylinder pressure, turbulence, mixture composition, electrode temperature, and polarity.

The 2.4× field-concentration result tells us the fine tip matters, but it does not tell us how much firing voltage is actually saved. For that, we need a different comparison.

### Modeled Comparison: IT16TT vs. a Conventional Plug

To compare the two plugs on equal terms, I ran both through the same breakdown model. The gas properties (an air ionization coefficient scaled for density), the breakdown criterion (the voltage at which ionization accumulated across the gap reaches a threshold), the gap, and the two load conditions (5 bar / 600 K and 13 bar / 720 K) were identical. Only the electrode geometry changed:

- **Conventional plug:** 1.25 mm center-electrode tip radius facing a flat ground strap.
- **Denso IT16TT:** 0.2 mm center-electrode tip radius facing a 0.35 mm-radius ground tip (the 0.7 mm Twin-Tip platinum electrode).

Because the breakdown threshold is uncertain, I ran the model two ways and present the results as ranges. I also show the results mainly as percentage reductions rather than absolute kilovolts, because the plug-to-plug comparison is more useful here than any individual modeled voltage. The exact assumptions and limitations are in Appendix C.

Here is how to read the results. A "regular plug" below means the conventional large-electrode plug used for the conventional rows of the first table. Each number is how much *less* voltage the ignition system has to produce to make the spark jump the gap, so a bigger number means an easier job for the coil, cap, rotor, and wires. "Cruising" means light load, and "towing" stands in for hard acceleration, climbing a grade, or pulling a trailer, when cylinder pressure is highest. Each result is a range because I ran the model with two different settings to see how much the answer moves.

| What changes | Cruising / light load | Towing / hard acceleration |
| --- | --- | --- |
| Keep the .040" gap, but switch from a regular plug to the IT16TT (the plug design alone) | 12–22% less voltage | 15–24% less voltage |
| Go from a regular .060" plug to the IT16TT at .040" (both changes together) | 33–41% less voltage | 36–42% less voltage |
| Keep a regular plug, but close the gap from .060" to .040" (the gap alone) | about 24% less voltage | about 24% less voltage |

As an example, if a regular plug at .060" needed 20,000 volts at a given moment, the IT16TT at .040" would need roughly 12,000 to 13,000 volts in this model.

![Grouped bar chart of estimated spark voltage needed under light and heavy load: a regular .060 inch plug is the 100 percent baseline at light load and about 190 percent under heavy load; a regular plug at .040 inch needs about 76 and 144 percent; the Denso IT16TT at .040 inch needs about 63 and 116 percent](modeled-voltage-reduction.png)

*The same results in simplest form: how much voltage the ignition system has to produce, compared with a regular plug at the factory .060" gap under light load (100%). Heavy load roughly doubles the requirement for every plug in this model, but the tighter gap and the IT16TT take a similar share off in both conditions. Values are the middle of the ranges in the table above.*

In this model, the ~.040-inch IT16TT lands in roughly the same firing-voltage neighborhood as a conventional plug at about .028–.034 inch, depending on load and threshold. That is consistent with the calculated IT16TT row in the first table, whose 13–17% reduction at the same gap falls inside the modeled range. (That row's own adjustment corresponds to about .032–.034 inch; the two methods differ slightly but agree on the scale.)

For the practical question of staying with a conventional .060-inch plug versus moving to the IT16TT, the comparison is roughly a 33–42% reduction in required voltage. About 24 points of that come from the tighter gap, which follows from well-established breakdown behavior. (That is a little smaller than the roughly 29–30% difference between the .040-inch and .060-inch rows in the first table, because the non-uniform field near a curved tip makes required voltage scale slightly less steeply with gap than the uniform-field fit used there.) The rest comes from the fine-wire geometry, which is the less certain part.

Three limitations are worth stating plainly:

1. **The result depends on the assumed tip shapes.** Varying the conventional plug's assumed tip radius from 0.75 to 2.0 mm moved the same-gap reduction between about 7% and 28%. Also varying the IT16TT's assumed tip radii (0.15–0.25 mm center, 0.25–0.35 mm ground) widens that to roughly 4% to 35%. If the conventional plug's ground-strap edge is modeled as slightly rounded rather than flat, the IT16TT advantage shrinks toward the low end of that span.
2. **The ground electrode does not add field enhancement the way I first assumed.** Compared with a flat ground, a small ground tip at the same gap actually lowers the field at the center tip (from about 3.5 to about 2.6 per mm per volt) while creating a second, weaker concentration at its own tip (about 1.7 per mm per volt). Whatever the 0.7 mm platinum ground electrode contributes is more likely to come from reduced flame-kernel quenching and better wear behavior than from additional field concentration.
3. **The model still leaves out the in-cylinder complexity.** It does not include turbulence, mixture composition, electrode temperature, or polarity effects, and the load points are representative rather than measured L29 data. Only an ignition-scope measurement on a real engine could confirm the size of the benefit.

### Polarity, Temperature, and the Center Electrode

In a typical ignition system, the coil fires with the center electrode negative relative to the ground strap. The center electrode also normally operates hotter than the ground electrode, and hot metals emit electrons more readily than colder metals through a phenomenon known as thermionic emission (sometimes called the Edison effect). That higher temperature can therefore aid electron emission from the negatively charged center electrode. At the same time, the very small radius of a fine center electrode concentrates the local electric field at its tip. Both effects favor initiation of the discharge at the center electrode. For that reason, I suspect the IT16TT's 0.4 mm iridium center electrode is responsible for much of its lower firing-voltage demand. I would treat that as a reasonable interpretation rather than a measured allocation of exactly how much each part of the firing-end geometry contributes.

Taken together, those effects give another physical reason to expect the IT16TT to be somewhat easier to fire than a conventional plug at the same gap. The modeling above attempts to estimate the size of that difference; the important point here is simply that the small center electrode is likely doing much of the work. That remains an interpretation rather than a measured allocation on an L29.

Separately, the smaller electrodes may also offer a benefit by reducing obstruction and quenching around the developing flame kernel. A fine 0.7 mm ground electrode presents less physical material around the initial spark region than a conventional wide ground strap, although I can't say how significant that difference would be on an L29.

Iridium and platinum matter here because of durability, not because they are better electrical conductors than copper. Their resistance to heat and electrical erosion allows the electrodes to be made extremely small while still holding their shape and gap over time. In other words, the fine geometry provides the electrical advantage, while the precious metals make that geometry practical and durable.

## Other Practical Benefits of the Fine-Wire Design

Lower firing voltage is the headline benefit, but a fine-wire design also changes three other things that can be estimated with the same kind of simple calculation. As before, these are geometry-based estimates, not measured results. The supporting math is in Appendix D.

### Less Metal Around the Developing Spark

Once the spark jumps the gap, the flame kernel starts small and grows. The electrodes next to it pull heat out of the kernel, and the more electrode surface the kernel touches, the more heat it can lose. The IT16TT's electrodes are much smaller than a conventional plug's, so there is less metal for the kernel to touch.

To put a rough number on it, I treated the kernel as a sphere centered in the middle of a .040-inch gap and calculated how much of its surface touches each electrode. I modeled each electrode face as a flat disk: 2.5 mm wide for both faces of the regular plug (the same ~2.5 mm assumption used earlier), and 0.4 mm and 0.7 mm wide for the IT16TT's center and ground electrodes.

| Kernel radius | Regular plug: metal contact | Regular plug: share of kernel surface | IT16TT: metal contact | IT16TT: share of kernel surface |
| --- | --- | --- | --- | --- |
| 0.75 mm | 1.9 mm² | 27% | 0.5 mm² | 7% |
| 1.0 mm | 4.7 mm² | 37% | 0.5 mm² | 4% |
| 1.5 mm | 9.8 mm² | 35% | 0.5 mm² | 2% |
| 2.0 mm | 9.8 mm² | 20% | 0.5 mm² | 1% |

![Line chart of the estimated share of the flame kernel's surface touching metal as the kernel grows, showing a regular plug peaking near 43 percent and the Denso IT16TT peaking near 10 percent](kernel-electrode-contact.png)

*Estimated share of the flame kernel's surface touching metal, by kernel size. This is a geometric estimate, not a heat-loss measurement.*

In this simplified picture, a kernel 1.5 mm in radius has roughly a third of its surface touching metal on a regular plug, and about 2% on the IT16TT. Seen from the middle of the gap, the regular plug's two electrode faces also block about 62% of all directions, versus about 12% for the IT16TT.

Three cautions apply. First, this counts contact area and does not calculate actual heat loss, which also depends on gas flow, temperature, and how the kernel really grows. Real kernels are not spheres and get stretched by turbulence. Second, behind the fine tips the IT16TT has a wider insulator nose and shell, so once a kernel grows large enough to reach those, the difference narrows. The estimate says nothing about that later stage. Third, I can't say how much this matters on an L29. It does show that the claim about reduced obstruction has real geometry behind it, while any reduction in quenching remains an inference from that geometry.

### Why Holding the Tip Shape and Gap Matters

Two further calculations show why the iridium and platinum matter.

**Gap growth.** As a plug's gap wears open, its required voltage keeps climbing. Starting from .040 inch:

| Gap growth | Regular plug: more voltage needed | IT16TT: more voltage needed (model) |
| --- | --- | --- |
| +.005" (to .045") | 9–11% | 6–7% |
| +.010" (to .050") | 17–22% | 11–13% |
| +.015" (to .055") | 24–32% | 16–18% |
| +.020" (to .060") | 31–43% | 21–23% |

The regular-plug range spans the geometry model on the low end and the uniform-field formula from the first table on the high end. Every extra .005 inch of gap costs a regular plug roughly 9–11% more voltage at first, and the fine tip appears somewhat less sensitive in the model. I have no wear-rate data, so I have not tried to predict how fast any particular plug opens up. The point is that holding the gap is worth real voltage, and that is the job of the precious-metal electrodes.

**Tip shape.** The IT16TT's advantage depends on the tip staying small. Holding the gap at .040 inch and the ground tip fixed, here is how the modeled advantage over a regular plug changes as the effective radius of the center tip grows:

| Effective center-tip radius | IT16TT advantage over a regular plug at the same gap |
| --- | --- |
| 0.2 mm (as designed) | 12–24% |
| 0.3 mm | 7–14% |
| 0.4 mm | 5–10% |

Doubling the effective tip radius from 0.2 to 0.4 mm removes about 58% of the modeled advantage. This is a what-if sensitivity, not a wear prediction. It shows why the article keeps returning to preserving the firing geometry: the voltage benefit comes from the tip shape, so it only lasts as long as the tip does.

### How Much Ignition-System Degradation Can It Tolerate?

The most practical way to think about ignition reserve is to ask how much of the system's available voltage can be lost to aging, moisture, or leakage before the weakest cylinder misfires under the worst load. That depends on how much reserve the system starts with, which I don't know for any particular L29, so the table below tries three starting points. Margin here means how far the system's available voltage exceeds what a regular .060-inch plug needs under heavy load.

| Starting margin with a regular .060" plug | Regular plug, .060" | Regular plug, .040" | Denso IT16TT, .040" |
| --- | --- | --- | --- |
| 10% | 9% | 31% | 45% |
| 25% | 20% | 39% | 51% |
| 50% | 33% | 49% | 59% |

![Grouped bar chart of the share of available ignition voltage that can be lost before a misfire, for a regular .060 inch plug, a regular .040 inch plug, and the Denso IT16TT, at starting margins of 10, 25, and 50 percent](ignition-degradation-tolerance.png)

*Share of available ignition voltage that can be lost before the weakest cylinder misfires under heavy load. Calculated, relative model results.*

For example, if a system has 25% reserve with a regular .060-inch plug, it can lose about 20% of its available voltage before misfiring. With a regular plug at .040 inch, it could lose about 39%. With the IT16TT at .040 inch, about 51%. The tighter the starting margin, the more a lower-demand plug helps. Two caveats: this uses only the relative heavy-load results from earlier, not absolute voltages, and it assumes the system's available voltage does not depend on which plug is installed.

## Breakdown Voltage Is Not the Whole Spark

The voltage required to start the spark and the energy delivered after the gap breaks down are related but different things. Once the gap ionizes, the voltage across it falls sharply and current can flow through the plasma channel. The ignition coil then continues releasing stored magnetic energy for a finite period of time, producing what is usually referred to as spark duration or burn time.

How much energy the coil has available depends in part on how much primary current was allowed to build before the spark event. That charging period is commonly referred to as dwell time. Because an ignition coil is an inductive device, its primary current takes time to rise toward saturation; it does not reach full stored energy instantaneously. More dwell can allow greater primary current and stored magnetic energy up to the point where the coil approaches saturation. Beyond that point, additional dwell provides little useful increase in spark energy and mainly increases heating in the coil and switching electronics.

Engine speed matters as well. As RPM increases, there is less physical time available between ignition events. The ignition-control system therefore has to manage dwell so the coil has adequate time to build energy before it is fired again. A coil or ignition system that performs perfectly well at idle can have less reserve at higher engine speed or under heavy load, particularly if primary voltage, wiring, grounds, the coil, or the switching electronics are marginal.

Enough spark duration and energy are needed to establish a stable flame kernel, particularly when mixture conditions are less favorable. A plug that is easier to initiate does not automatically create a longer spark or more spark energy, but requiring less voltage to establish the discharge leaves more voltage margin for reliably initiating the event.

That distinction is worth keeping in mind because a spark plug is not simply asking the ignition system for a particular voltage. The ignition system first has to produce enough voltage to break down the gap, and then it still has to deliver enough energy through the resulting plasma channel to reliably start combustion. Firing voltage is therefore one important part of the event, but not the whole event.

## Heat Range Still Matters

None of this changes the importance of choosing the correct plug heat range. Heat range describes how quickly the firing end transfers heat into the cylinder head; it does not describe spark temperature or how "hot" the ignition system is.

A plug that runs too cold can be more prone to deposits and fouling, while one that runs too hot can allow the firing end to reach temperatures where pre-ignition and electrode damage become concerns.

For the IT16TT comparison, I relied on Denso's cross-reference rather than trying to directly translate ACDelco and Denso heat-range numbers. That matters particularly on a heavy vehicle such as an L29 Suburban because towing, climbing grades, high ambient temperatures, and sustained load can keep combustion-chamber and plug temperatures elevated for much longer than a short acceleration run. I would not choose a different heat range simply because a particular electrode design or gap looks attractive.

## Choose a Plug Designed for the Gap You Want

Another thing I took away from the discussion is that taking a plug configured around .060 inch and bending the ground strap all the way down to .040 inch is not necessarily the same as starting with a plug whose firing-end geometry is already set up near .040 inch. Moving the strap a large amount changes its relationship to the center electrode.

Fine-wire plugs also deserve some care. The small iridium and platinum firing surfaces are durable in service but can be easily damaged during gap adjustment, and most advice I have seen is to avoid adjusting them unless absolutely necessary. Since the IT16TT already comes very close to the gap I want, my plan is simply to carefully verify the gaps when they arrive and leave the electrodes alone.

A few practical installation notes follow from that. A round wire-style gauge is the better tool for checking a fine-wire plug, since a flat feeler blade can catch on the small electrodes, and nothing should ever be pried against the center electrode. Be sure to check the vehicle's service manual and the spark-plug manufacturer's documentation for proper torque and whether anti-seize should be used.

## What If You Want to Stay Near the .060-Inch Spec?

There is also a reasonable case for staying near the .060-inch specification and simply choosing a better plug design. The ACDelco 41-979 double-platinum plug is one example. GM lists it as a 1.6 mm / .060-inch gap plug, along with a 17.5 mm reach, tapered seat, and 16 mm hex. As with any plug, the application and plug specification should be verified when purchasing rather than assumed from appearance alone.

That does not eliminate the higher voltage demand of a wider gap, but a fine-wire platinum or iridium plug should generally be somewhat easier to fire than a traditional large-electrode plug at the same gap and should hold its firing geometry and gap better as the miles add up. In the same geometry model used earlier, an IT16TT-style fine tip at .060 inch comes out roughly 18–30% easier to fire than a regular .060-inch plug, which puts it about level with a regular .040-inch plug (within roughly 8% either way). It would still need about 21–23% more voltage than the same fine tip at .040 inch, which is why I prefer the tighter gap. The 41-979's tip may not be as fine as the 0.2 mm tip I modeled, so treat this as an illustration of the design approach and not a prediction for that specific plug (details in Appendix D).

So if someone wants to stay around the .060-inch specification, a fine-wire precious-metal plug seems like a better way to do it than a conventional large-electrode plug. It still uses more ignition reserve than a similar fine-wire plug around .040 inch, but the fine firing geometry can reduce some of the wider-gap penalty without changing the basic gap strategy itself — with how much depending on the exact electrode design.

## The Practical Takeaway

The more I looked at this, the less useful the usual "copper versus iridium" argument seemed. What really matters is the combination: correct thread, reach, seat, firing-end protrusion, and heat range; a sensible gap for the ignition system; electrode geometry; firing-voltage demand; gap growth over time; and how much ignition reserve remains when the engine is under its hardest load.

A conventional plug at .035–.045 inch can be easy to fire and work extremely well. A properly designed fine-wire iridium/platinum plug can do the same while maintaining its firing geometry and gap longer. On the other hand, a fine-wire plug with a very large gap can still demand a lot from the ignition system. There really is no magic plug.

For me, that is why the IT16TT makes sense on the L29. It gives me the gap range I want without having to force a wider-gap plug closed, and the fine-wire geometry should preserve a little more secondary-ignition margin while still giving the developing flame kernel good exposure. If my current ignition system is already firing every cylinder perfectly, I do not expect the plug itself to magically create additional horsepower. What I am looking for is a greater margin against ignition problems when cylinder pressure and firing demand are highest.

I expect my 1997 K2500 Suburban will run essentially the same as it would with a good set of R44LTS under ordinary conditions, while holding its firing geometry better and asking a little less from the crab-cap ignition system under load — and that is exactly what I am looking for. That expectation is consistent with the modeled numbers: against a regular plug at the same gap, the IT16TT's edge is a modest 12–24% in required voltage, which shows up as reserve and durability rather than as a change in how the truck drives.

And that same reasoning is not unique to Denso. It applies broadly to any properly designed fine-wire plug chosen with the engine, gap, heat range, and ignition system in mind.

## Parts Quality and Counterfeit Components

One other thing I think is worth mentioning is where these parts come from. With spark plugs, sensors, ignition components, and other critical engine-management parts, I think it makes sense to buy from the manufacturer directly or through a manufacturer-authorized reseller or distributor whenever possible. Counterfeit parts can look convincing enough to get installed, yet perform poorly or fail in ways that create entirely new symptoms. That can muddy the troubleshooting picture, make a good diagnosis look wrong, and even make someone blame the vehicle or the part design when the real problem is that the component was never genuine in the first place. When trying to evaluate ignition performance or chase an intermittent problem, eliminating questionable parts from the equation is just one more way to keep the test results meaningful. If you are interested in obtaining the Denso IT16TT spark plugs, please check the Denso 'Where to Buy' at https://www.densoautoparts.com/where-to-buy-passenger/.

## One Final Thought

Electrical breakdown is only the beginning of combustion. Once the spark forms, mixture quality, turbulence, fuel preparation, residual exhaust gases, temperature, and the energy delivered through the spark all influence whether a stable flame kernel develops.

That also circles back to all the other things that affect how well the engine burns the mixture once the spark is there: a good tune, healthy injectors with a proper spray pattern, correct fuel pressure, decent-quality gasoline, a clean air filter, accurate sensor inputs, good compression, and so on. The spark plug can only ignite the mixture it is given, and it is not a fix for existing problems in any of those areas regardless of marketing claims.

A conventional ignition system obviously does a pretty good job under normal conditions. What still interests me is how much of its available margin gets used up as pressure, gap, electrode shape, mixture conditions, component age, coil saturation, and spark-energy requirements all change. The spark itself is only the first tiny part of a much more complicated event.

## Acknowledgment

I also want to give Road Trip proper credit for the discussion that helped shape this write-up. His firsthand experience with older ignition analyzers, firing-voltage behavior under load, and marginal ignition systems added a practical perspective that helped keep this from becoming just a theoretical exercise. His broader troubleshooting philosophy — comparing weak performance against the best-performing example and continuing until the root cause is understood — also influenced the way I started thinking about ignition reserve rather than simply whether the system technically "works."

Thanks for reading through my rambling. Hopefully this has been informative and useful to someone else going down the same rabbit hole.  —Deepsiks

## Appendix: How the Numbers Were Calculated

This section is optional reading for anyone who wants to check the math. Nothing in the main article depends on it beyond what is already stated there.

### Appendix A: Firing Voltage vs. Gap (the First Table)

The conventional-plug rows come from a commonly used empirical fit for the breakdown voltage of air in a uniform electric field:

**V_b ≈ 24.22 · δd + 6.08 · √(δd)**

Here V_b is the breakdown voltage in kilovolts, d is the gap in centimeters, and δ is the relative air density, which is the pressure in atmospheres scaled by 293 K divided by the gas temperature:

**δ = (P / 1.01325 bar) × (293 K / T)**

Higher pressure packs more gas molecules into the gap, and a hotter gas has fewer of them, so δ captures both effects in one number.

**Worked example: conventional plug at .040 inch (d = 0.1016 cm)**

*Light load (5 bar, 600 K):*
- δ = (5 / 1.01325) × (293 / 600) = 4.935 × 0.488 = 2.41
- δd = 2.41 × 0.1016 = 0.245
- V_b = 24.22 × 0.245 + 6.08 × √0.245 = 5.93 + 3.01 = **8.9 kV**

*Heavy load (13 bar, 720 K):*
- δ = (13 / 1.01325) × (293 / 720) = 12.83 × 0.407 = 5.22
- δd = 5.22 × 0.1016 = 0.530
- V_b = 24.22 × 0.530 + 6.08 × √0.530 = 12.85 + 4.43 = **17.3 kV**

Every other conventional row uses the same steps with a different gap. At .060 inch (d = 0.1524 cm), light load gives δd = 0.367 and V_b = 8.89 + 3.68 = **12.6 kV**, and heavy load gives δd = 0.796 and V_b = 19.27 + 5.42 = **24.7 kV**.

The two terms explain a pattern in the table. The first term is proportional to gap, but the square-root term grows more slowly, so voltage rises a little less than the gap does. Going from .035 to .060 inch makes the gap 71% larger, yet the required voltage rises only 57% under light load and 60% under heavy load.

**The IT16TT row.** Because this formula assumes a uniform field, it knows nothing about electrode shape. For the IT16TT, I evaluated the same formula at a smaller effective gap. Working backward from the table, the 7.4 kV and 15.0 kV values correspond to effective gaps of about .032 inch under light load and .034 inch under heavy load, roughly 20% and 15% smaller than the real .040-inch gap. That adjustment is a judgment call, not a measurement. The geometry model in Appendix C is an independent cross-check, and it points to a similar range.

**Limits of this method.** The fit was developed for air at around atmospheric pressure, so applying it at 5 to 13 bar is an extrapolation. It also assumes a uniform field between flat electrodes, and the load points are representative rather than measured. That is why I treat the table as showing trends in gap and load, not as predictions of what the L29 will actually require.

### Appendix B: Field Concentration at the Tip

**Rough formula.** A common point-to-plane (hyperboloid) approximation for the peak electric field at a tip is:

**E_max ≈ 2V / (r · ln(4d/r))**

Here V is the applied voltage, r is the tip radius, and d is the gap. At d = 1.016 mm:

- **Conventional (r = 1.25 mm):** 4d/r = 4.064 / 1.25 = 3.25, so ln(4d/r) = 1.18. Then r · ln(4d/r) = 1.47 mm, and E_max / V ≈ 2 / 1.47 ≈ **1.4 per mm**.
- **IT16TT (r = 0.2 mm):** 4d/r = 4.064 / 0.2 = 20.3, so ln(4d/r) = 3.01. Then r · ln(4d/r) = 0.60 mm, and E_max / V ≈ 2 / 0.60 ≈ **3.3 per mm**.

**Exact solution.** For a hyperboloid tip facing a flat plane, the peak field can be written exactly. Define η₀ = √(d / (d + r)) and a = d / η₀. Then:

**E_max / V = 1 / ( a · atanh(η₀) · r/(d + r) )**

- **Conventional (r = 1.25 mm):** η₀ = 0.670, a = 1.517 mm, atanh(η₀) = 0.810, r/(d + r) = 0.552. E_max / V = 1 / (1.517 × 0.810 × 0.552) ≈ **1.47 per mm**.
- **IT16TT (r = 0.2 mm):** η₀ = 0.914, a = 1.112 mm, atanh(η₀) = 1.552, r/(d + r) = 0.164. E_max / V = 1 / (1.112 × 1.552 × 0.164) ≈ **3.53 per mm**.

The ratio of the two exact values is 3.53 / 1.47 ≈ 2.4, the same as with the rough formula. The rough formula runs slightly low for both electrodes. The exact solution is the better number, especially for the conventional plug, where the gap and the tip radius are similar in size and the shortcut is least accurate.

### Appendix C: The Breakdown Model for the Plug Comparison

For anyone who wants to check the method: the field along the gap axis comes from the exact solution for a hyperboloid tip facing a plane (or a second, confocal hyperboloid for the Twin-Tip ground electrode). Gas ionization uses a Townsend-type coefficient for air, α/p = A·exp(−B·p/E) with A = 15 cm⁻¹·Torr⁻¹ and B = 365 V/(cm·Torr), with pressure scaled to a 293 K equivalent density. Breakdown is declared at the voltage where the ionization coefficient integrated along the gap axis reaches a threshold K.

The threshold is the least certain input, so I ran two values to bracket the answer. K = 18 is a typical streamer-breakdown criterion. K ≈ 1.3 is the value that makes a uniform-field gap reproduce the baseline in the first table; it is low enough that I don't consider it physically realistic, but it keeps the two parts of this article on the same footing. One further caution: these ionization constants are normally quoted for field-to-pressure ratios of roughly 100–800 V/(cm·Torr), and in this model most of the gap sits below that range, with only the region right at the tip reaching it. That is another reason to trust the plug-to-plug percentages more than any individual voltage value.

### Appendix D: The Fine-Wire Design Estimates

**Flame-kernel contact.** Model the kernel as a sphere of radius R centered midway across the gap, so its center is h = d/2 = 0.508 mm from each electrode face. When R is larger than h, the sphere meets each face plane in a circle of radius √(R² − h²), limited by the size of the face itself. The contact area on a face of radius r_f is therefore:

**A = π · min(R² − h², r_f²)**

and the share of the kernel's surface touching metal is the total contact area divided by 4πR².

*Worked example, R = 1.5 mm:* R² − h² = 2.25 − 0.258 = 1.99 mm², so the circle radius is 1.41 mm, larger than any of the faces.
- **Regular plug (two faces, r_f = 1.25 mm):** each face contributes π × 1.25² = 4.91 mm², for 9.82 mm² total. Kernel surface = 4π × 1.5² = 28.3 mm². Share = 9.82 / 28.3 = **34.7%**.
- **IT16TT (r_f = 0.2 mm and 0.35 mm):** π × 0.2² + π × 0.35² = 0.126 + 0.385 = 0.51 mm². Share = 0.51 / 28.3 = **1.8%**.

*Directions blocked.* A disk of radius r_f at distance h covers a fraction ½ × (1 − h / √(h² + r_f²)) of all directions seen from the kernel's center. For the regular plug, each face covers ½ × (1 − 0.508 / 1.349) = 0.312, so both cover about **62%**. For the IT16TT, the center electrode covers ½ × (1 − 0.508 / 0.546) = 0.035 and the ground electrode ½ × (1 − 0.508 / 0.617) = 0.088, about **12%** together.

**Gap growth.** The regular-plug ranges combine two sources: the geometry model from Appendix C (conventional tip, 1.25 mm radius, facing a flat ground) and the uniform-field formula from Appendix A. The IT16TT values come from the Appendix C model alone, using the same two thresholds and both load conditions. The uniform-field formula rises faster with gap than the geometry model does, for the reason given earlier in the article.

**Tip shape.** The same Appendix C model, with the IT16TT's center-tip radius set to 0.2, 0.3, and 0.4 mm, the ground tip fixed at 0.35 mm, and the gap at .040 inch, compared against the regular plug. Both thresholds and both load conditions were run, and the 58% reduction in advantage at 0.4 mm held in all four cases.

**Degradation tolerance.** Let R₆₀ be the heavy-load voltage requirement of a regular .060-inch plug, and let the system's available voltage be (1 + M) × R₆₀, where M is the starting margin. The share of available voltage that can be lost before a misfire is 1 − (requirement ÷ available voltage). From the heavy-load results earlier in the article, a regular .040-inch plug needs about 0.76 × R₆₀ (24% less), and the IT16TT needs about 0.61 × R₆₀ (the middle of the 36–42% range, 39% less).

*Worked example, M = 25%:* available voltage = 1.25 × R₆₀.
- Regular .060": 1 − 1.00 / 1.25 = **20%**
- Regular .040": 1 − 0.76 / 1.25 = **39%**
- IT16TT .040": 1 − 0.61 / 1.25 = **51%**

**Fine tip at .060 inch.** The same Appendix C model, with an IT16TT-style tip (0.2 mm center radius, 0.35 mm ground radius) at a .060-inch gap (1.524 mm), compared three ways. Against a regular plug at .060 inch, it requires 18–30% less voltage. Against the same fine tip at .040 inch, it requires 21–23% more. Against a regular plug at .040 inch, it requires between 8% less and 8% more, depending on the threshold and load. Both thresholds and both load conditions were run.
