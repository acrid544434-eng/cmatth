00_COVER/
  └─ CHIMERA_501P_COVER_EDITION_WITH_3D_RENDER.pdf (501 pages, hero chip on cover)

01_DISCS/
  ├─ CHIMERA_500P_LAFAYETTE_UPDATED.pdf (Lafayette spec: 3nm / 512-TPU / 1000W / AES-256-GCM + ML-KEM-1024 / OCS)
  └─ CHIMERA_500P_ORIGINAL_SHREVEPORT.pdf (Original for provenance)

02_EXECUTIVE/
  └─ CHIMERA_2P_EXECUTIVE_SUMMARY.pdf (Plain-English + technical impact)

03_SIMULATION/ - FULL SIMULATION TESTING ABSOLUTE DETAILS - ALL PASS
  ├─ FULL_SIMULATION_REPORT_ABSOLUTE_DETAILS.pdf
  ├─ LOGS/
  │   ├─ RTL_SIMULATION_FULL.log (10,000 cycles, 100% coverage, 6 formal proofs PROVEN)
  │   ├─ FPGA_EMULATION_FULL.log (Alveo/Versal, 1.73% latency, 1.91% BW, <2%)
  │   ├─ SIDE_CHANNEL_TVLA_EM_FULL.log (500k traces, t<4.5, 0 leakage, 12us zeroize)
  │   └─ CLUSTER_64N_OCS_FULL.log (64-node, 92.8% linear, 102.4 Tbps, NDR equiv)
  └─ SCRIPTS/
      ├─ chimera_top_tb.sv
      ├─ benchmark_fpga.py
      ├─ tvla_em_analysis.py
      └─ cluster_ocs_torus_sim.py

04_RENDERS/
  ├─ CHIP_512TPU_1000W_VC_COVER.jpg (Photorealistic hero)
  └─ CHIP_512TPU_1000W_VC_ORIGINAL.webp

05_BLUEPRINTS/
  ├─ BLUEPRINT_PRODUCTION_READY_PACKAGE.jpg (Rev 1.3/1.1/1.0)
  ├─ BLUEPRINT_VALIDATION_PATHWAY.jpg (RTL 100%, FPGA <2%, Side-Channel, 64-Node)
  └─ BLUEPRINT_ORIGINAL_ARCHITECTURE.jpg (Secure Enclave original)

06_ARCHIVAL/
  └─ Previous packages for chain of custody

README_MASTER_SUBMISSION.txt + MANIFEST.txt