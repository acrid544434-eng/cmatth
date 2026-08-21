baac-se-v1.0/
  docs/
    BAAC-SE-Overview.md
    Astrophysics-Ingestion.md
    CKKS-Pipeline.md
    ZK-Bounded-Error-Architecture.md
    Groth16-R1CS-QAP.md
    OS-RT-Kernel-Config.md
    Bionic-Actuation-Safety.md

  src/
    core/
      telemetry_ingest.cpp
      ckks_encrypt_eval.cpp
      residual_witness.cpp
      groth16_prover.cpp
      groth16_verifier.cpp
    runtime/
      bionic_crypto_pipeline.cpp
      hardware_interrupts.cpp
      actuator_dispatch.cpp
      audit_logging.cpp
      secure_export.cpp
    zk/
      r1cs_constraints.cpp
      qap_compiler.cpp
      vk_pk_loader.cpp
    os_rt/
      core_affinity_manager.cpp
      rt_scheduling.cpp

  include/
    telemetry.hpp
    ckks.hpp
    zk_witness.hpp
    groth16.hpp
    pipeline.hpp
    audit.hpp
    os_rt.hpp

  config/
    kernel_boot_params.conf
    core_affinity_profiles.json
    error_bounds.yaml
    vk_pk_manifest.json

  tests/
    unit/
      test_ckks_precision.cpp
      test_residual_bounds.cpp
      test_groth16_verification.cpp
      test_actuator_interlock.cpp
    integration/
      test_full_pipeline_rt.cpp
      test_external_audit_stream.cpp

  scripts/
    setup_kernel_isolation.sh
    deploy_vk_pk.sh
    run_baac_se_rt.sh

  audit/
    sample_ledger_dump.bin
    merkle_roots.log
    external_node_protocol.md