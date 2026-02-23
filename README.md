# FS-Regenerative-Battery-Model
Impact: Boosted energy recovery from &lt;1% to 20% per lap. I diagnosed critical hardware flaws in the BMS (IC supply/isolation) and developed a high-fidelity Battery Model (ECM) via experimental Cell Testing. This allowed the team to break a 7-year streak and complete the 22km Endurance Event for the first time since 2017.

🏎 Real-World Validation: Breaking the Endurance Curse
Context & Strategy
In Formula Student, the Endurance Event (22km) is the ultimate test. For 7 years, the team struggled to finish due to a "Weight-Regen Paradox": we carried a heavy 7-8 kWh battery because we lacked efficient regeneration, but we couldn't reduce weight without a proven regen system.

My role was to break this cycle by proving that we could push the battery limits safely.

1. Hardware Recovery & Track Success
Before building any models, we had to fix the foundation. I performed a deep diagnostic of the legacy BMS (Battery Management System), identifying critical flaws in the IC supply architecture and isolation transformer terminations.

The Result: With a stable BMS and a new regeneration strategy, we didn't just compete; we finished the two most prestigious Formula Student competitions in the world. We moved from a negligible <1% energy recovery to a solid 20% per lap, proving the system's reliability under real racing conditions.

2. Experimental Validation (The Melasta Test)
To justify this 20% regen, I had to challenge the manufacturer's (Melasta) conservative limits:

The Insight: Analysis of previous years' data showed that cell temperatures remained stable at peak currents.

The Test: I built a custom cell testbench to stress-test the Li-ion cells. I demonstrated that our thermal management could handle significantly higher charge currents than specified in the standard datasheet.

Efficiency: By pushing the battery closer to its 600V limit, we leveraged the Joule Effect to minimize losses, maximizing every joule recovered during braking.

3. The Predictive Model (Post-Race Engineering)
Once the system was proven on track, I developed a Battery Equivalent Circuit Model (ECM).

Purpose: This model wasn't just a theoretical exercise; it was built using the successful track data and cell tests to perform Weight Reduction Simulations.

Legacy: The model now serves as the roadmap for future seasons, providing the empirical proof needed to downsize the battery pack (weight reduction) while maintaining the energy security required to finish an Endurance.

🏆 Key Achievements
Reliability: Successfully finished 2 world-class Endurance events (first time in 7 years).

Efficiency: 20% energy recovery per lap.

Future-Proofing: Developed the ECM for next-gen weight reduction strategies.
