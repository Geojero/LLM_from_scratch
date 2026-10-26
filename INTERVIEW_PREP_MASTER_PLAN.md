# 🎯 Complete Interview Preparation — Master Plan

> **Goal:** Build confidence to write code from memory in interviews. You know the stuff — these notebooks make you **fluent** again.

> **Style:** Same as DSA notebooks — conversational, ASCII art, emojis, step-by-step code you can reproduce under pressure.

---

## 📊 Overview

| #   | Subject                   | Chapters | Modules  | Focus                                             |
| --- | ------------------------- | -------- | -------- | ------------------------------------------------- |
| 1   | Operating Systems         | 5        | 18       | Theory + Interview Q&A                            |
| 2   | DBMS & SQL                | 5        | 20       | Theory + Write SQL from memory                    |
| 3   | Computer Networks         | 5        | 16       | Theory + Protocol deep-dives                      |
| 4   | OOP & Design Patterns     | 5        | 20       | Python code for every pattern                     |
| 5   | System Design (LLD + HLD) | 5        | 22       | Draw + code designs on whiteboard                 |
| 6   | Backend & FastAPI         | 6        | 22       | Build APIs from scratch confidently               |
| 7   | ML / DL Code Fluency      | 7        | 28       | Write PyTorch/TF/sklearn/NumPy/Pandas from memory |
|     | **TOTAL**                 | **38**   | **~146** |                                                   |

---

## 📁 Folder Structure

```
OS-Quick-Prep-Notes/
├── chapter_01_process_management/
│   ├── module_01_processes/
│   │   └── day_01a_processes.ipynb
│   ├── module_02_threads/
│   │   └── day_02a_threads.ipynb
│   ├── module_03_cpu_scheduling/
│   │   └── day_03a_cpu_scheduling.ipynb
│   └── module_04_inter_process_communication/
│       └── day_04a_ipc.ipynb
├── chapter_02_synchronization/
│   ├── module_01_critical_section/
│   │   └── day_01a_critical_section.ipynb
│   ├── module_02_mutex_semaphore/
│   │   └── day_02a_mutex_semaphore.ipynb
│   ├── module_03_classic_problems/
│   │   └── day_03a_classic_sync_problems.ipynb
│   └── module_04_deadlocks/
│       └── day_04a_deadlocks.ipynb
├── chapter_03_memory_management/
│   ├── module_01_memory_basics/
│   │   └── day_01a_memory_basics.ipynb
│   ├── module_02_paging/
│   │   └── day_02a_paging.ipynb
│   ├── module_03_virtual_memory/
│   │   └── day_03a_virtual_memory.ipynb
│   └── module_04_page_replacement/
│       └── day_04a_page_replacement.ipynb
├── chapter_04_file_systems/
│   ├── module_01_file_organization/
│   │   └── day_01a_file_organization.ipynb
│   ├── module_02_disk_scheduling/
│   │   └── day_02a_disk_scheduling.ipynb
│   └── module_03_io_systems/
│       └── day_03a_io_systems.ipynb
└── chapter_05_linux_essentials/
    ├── module_01_process_commands/
    │   └── day_01a_process_commands.ipynb
    ├── module_02_file_permissions/
    │   └── day_02a_file_permissions.ipynb
    └── module_03_shell_scripting/
        └── day_03a_shell_scripting.ipynb

DBMS-Quick-Prep-Notes/
├── chapter_01_fundamentals/
│   ├── module_01_rdbms_basics/
│   │   └── day_01a_rdbms_basics.ipynb
│   ├── module_02_er_model/
│   │   └── day_02a_er_model.ipynb
│   ├── module_03_keys_constraints/
│   │   └── day_03a_keys_constraints.ipynb
│   └── module_04_normalization/
│       └── day_04a_normalization.ipynb
├── chapter_02_sql_mastery/
│   ├── module_01_select_basics/
│   │   └── day_01a_select_basics.ipynb
│   ├── module_02_joins/
│   │   └── day_02a_joins.ipynb
│   ├── module_03_subqueries_ctes/
│   │   └── day_03a_subqueries_ctes.ipynb
│   ├── module_04_window_functions/
│   │   └── day_04a_window_functions.ipynb
│   └── module_05_sql_practice/
│       └── day_05a_sql_practice.ipynb
├── chapter_03_transactions/
│   ├── module_01_acid_properties/
│   │   └── day_01a_acid.ipynb
│   ├── module_02_concurrency_control/
│   │   └── day_02a_concurrency_control.ipynb
│   ├── module_03_isolation_levels/
│   │   └── day_03a_isolation_levels.ipynb
│   └── module_04_deadlocks_recovery/
│       └── day_04a_deadlocks_recovery.ipynb
├── chapter_04_indexing/
│   ├── module_01_btree_indexing/
│   │   └── day_01a_btree_indexing.ipynb
│   ├── module_02_hash_indexing/
│   │   └── day_02a_hash_indexing.ipynb
│   └── module_03_query_optimization/
│       └── day_03a_query_optimization.ipynb
└── chapter_05_advanced/
    ├── module_01_nosql_concepts/
    │   └── day_01a_nosql.ipynb
    ├── module_02_cap_theorem/
    │   └── day_02a_cap_theorem.ipynb
    └── module_03_sharding_replication/
        └── day_03a_sharding_replication.ipynb

CN-Quick-Prep-Notes/
├── chapter_01_network_models/
│   ├── module_01_osi_model/
│   │   └── day_01a_osi_model.ipynb
│   ├── module_02_tcp_ip_model/
│   │   └── day_02a_tcp_ip_model.ipynb
│   └── module_03_encapsulation/
│       └── day_03a_encapsulation.ipynb
├── chapter_02_application_layer/
│   ├── module_01_http_https/
│   │   └── day_01a_http_https.ipynb
│   ├── module_02_dns/
│   │   └── day_02a_dns.ipynb
│   ├── module_03_email_protocols/
│   │   └── day_03a_email_protocols.ipynb
│   └── module_04_rest_websocket/
│       └── day_04a_rest_websocket.ipynb
├── chapter_03_transport_layer/
│   ├── module_01_tcp_deep_dive/
│   │   └── day_01a_tcp.ipynb
│   ├── module_02_udp/
│   │   └── day_02a_udp.ipynb
│   └── module_03_flow_congestion_control/
│       └── day_03a_flow_congestion.ipynb
├── chapter_04_network_layer/
│   ├── module_01_ip_addressing/
│   │   └── day_01a_ip_addressing.ipynb
│   ├── module_02_subnetting/
│   │   └── day_02a_subnetting.ipynb
│   ├── module_03_routing/
│   │   └── day_03a_routing.ipynb
│   └── module_04_nat_ipv6/
│       └── day_04a_nat_ipv6.ipynb
└── chapter_05_security/
    ├── module_01_ssl_tls/
    │   └── day_01a_ssl_tls.ipynb
    └── module_02_encryption_vpn/
        └── day_02a_encryption_vpn.ipynb

OOP-Design-Patterns-Quick-Prep-Notes/
├── chapter_01_oop_fundamentals/
│   ├── module_01_classes_objects/
│   │   └── day_01a_classes_objects.ipynb
│   ├── module_02_encapsulation_abstraction/
│   │   └── day_02a_encapsulation_abstraction.ipynb
│   ├── module_03_inheritance/
│   │   └── day_03a_inheritance.ipynb
│   └── module_04_polymorphism/
│       └── day_04a_polymorphism.ipynb
├── chapter_02_solid_principles/
│   ├── module_01_srp_ocp/
│   │   └── day_01a_srp_ocp.ipynb
│   ├── module_02_lsp_isp/
│   │   └── day_02a_lsp_isp.ipynb
│   └── module_03_dip/
│       └── day_03a_dip.ipynb
├── chapter_03_creational_patterns/
│   ├── module_01_singleton_factory/
│   │   └── day_01a_singleton_factory.ipynb
│   ├── module_02_abstract_factory_builder/
│   │   └── day_02a_abstract_factory_builder.ipynb
│   └── module_03_prototype/
│       └── day_03a_prototype.ipynb
├── chapter_04_structural_patterns/
│   ├── module_01_adapter_decorator/
│   │   └── day_01a_adapter_decorator.ipynb
│   ├── module_02_facade_proxy/
│   │   └── day_02a_facade_proxy.ipynb
│   └── module_03_composite_flyweight/
│       └── day_03a_composite_flyweight.ipynb
└── chapter_05_behavioral_patterns/
    ├── module_01_observer_strategy/
    │   └── day_01a_observer_strategy.ipynb
    ├── module_02_command_state/
    │   └── day_02a_command_state.ipynb
    ├── module_03_template_iterator/
    │   └── day_03a_template_iterator.ipynb
    └── module_04_chain_mediator/
        └── day_04a_chain_mediator.ipynb

System-Design-Quick-Prep-Notes/
├── chapter_01_fundamentals/
│   ├── module_01_scalability_basics/
│   │   └── day_01a_scalability.ipynb
│   ├── module_02_consistency_availability/
│   │   └── day_02a_cap_consistency.ipynb
│   ├── module_03_latency_throughput/
│   │   └── day_03a_latency_throughput.ipynb
│   └── module_04_estimation/
│       └── day_04a_back_of_envelope.ipynb
├── chapter_02_building_blocks/
│   ├── module_01_load_balancer_cdn/
│   │   └── day_01a_lb_cdn.ipynb
│   ├── module_02_caching/
│   │   └── day_02a_caching.ipynb
│   ├── module_03_databases/
│   │   └── day_03a_database_choices.ipynb
│   ├── module_04_message_queues/
│   │   └── day_04a_message_queues.ipynb
│   └── module_05_api_gateway_proxy/
│       └── day_05a_api_gateway.ipynb
├── chapter_03_lld/
│   ├── module_01_parking_lot/
│   │   └── day_01a_parking_lot.ipynb
│   ├── module_02_lru_cache/
│   │   └── day_02a_lru_cache_design.ipynb
│   ├── module_03_rate_limiter/
│   │   └── day_03a_rate_limiter.ipynb
│   ├── module_04_elevator_system/
│   │   └── day_04a_elevator.ipynb
│   ├── module_05_booking_system/
│   │   └── day_05a_booking_system.ipynb
│   └── module_06_snake_game/
│       └── day_06a_snake_game.ipynb
├── chapter_04_hld/
│   ├── module_01_url_shortener/
│   │   └── day_01a_url_shortener.ipynb
│   ├── module_02_twitter/
│   │   └── day_02a_twitter.ipynb
│   ├── module_03_instagram/
│   │   └── day_03a_instagram.ipynb
│   ├── module_04_chat_system/
│   │   └── day_04a_whatsapp.ipynb
│   ├── module_05_video_streaming/
│   │   └── day_05a_netflix_youtube.ipynb
│   └── module_06_ride_sharing/
│       └── day_06a_uber.ipynb
└── chapter_05_interview_framework/
    └── module_01_approach/
        └── day_01a_sd_interview_framework.ipynb

Backend-FastAPI-Quick-Prep-Notes/
├── chapter_01_web_fundamentals/
│   ├── module_01_http_basics/
│   │   └── day_01a_http_methods_status.ipynb
│   ├── module_02_rest_principles/
│   │   └── day_02a_rest_api_design.ipynb
│   ├── module_03_wsgi_asgi/
│   │   └── day_03a_wsgi_asgi.ipynb
│   └── module_04_api_best_practices/
│       └── day_04a_api_best_practices.ipynb
├── chapter_02_fastapi_core/
│   ├── module_01_hello_fastapi/
│   │   └── day_01a_hello_fastapi.ipynb
│   ├── module_02_path_query_params/
│   │   └── day_02a_path_query_params.ipynb
│   ├── module_03_pydantic_models/
│   │   └── day_03a_pydantic_validation.ipynb
│   ├── module_04_dependency_injection/
│   │   └── day_04a_dependency_injection.ipynb
│   └── module_05_middleware_cors/
│       └── day_05a_middleware_cors.ipynb
├── chapter_03_database_integration/
│   ├── module_01_sqlalchemy_orm/
│   │   └── day_01a_sqlalchemy.ipynb
│   ├── module_02_alembic_migrations/
│   │   └── day_02a_alembic.ipynb
│   ├── module_03_async_databases/
│   │   └── day_03a_async_db.ipynb
│   └── module_04_mongodb_motor/
│       └── day_04a_mongodb_motor.ipynb
├── chapter_04_auth_security/
│   ├── module_01_jwt_auth/
│   │   └── day_01a_jwt_auth.ipynb
│   ├── module_02_oauth2/
│   │   └── day_02a_oauth2.ipynb
│   └── module_03_security_best_practices/
│       └── day_03a_security_practices.ipynb
├── chapter_05_async_processing/
│   ├── module_01_async_await/
│   │   └── day_01a_async_await.ipynb
│   ├── module_02_celery_redis/
│   │   └── day_02a_celery_redis.ipynb
│   ├── module_03_websockets/
│   │   └── day_03a_websockets.ipynb
│   └── module_04_background_tasks/
│       └── day_04a_background_tasks.ipynb
└── chapter_06_deployment/
    ├── module_01_docker/
    │   └── day_01a_docker.ipynb
    ├── module_02_docker_compose/
    │   └── day_02a_docker_compose.ipynb
    └── module_03_cicd/
        └── day_03a_cicd_basics.ipynb

ML-DL-Code-Fluency-Notes/
├── chapter_01_numpy_mastery/
│   ├── module_01_array_creation_ops/
│   │   └── day_01a_numpy_arrays.ipynb
│   ├── module_02_broadcasting_vectorization/
│   │   └── day_02a_broadcasting.ipynb
│   ├── module_03_linear_algebra/
│   │   └── day_03a_linalg.ipynb
│   └── module_04_numpy_tricks/
│       └── day_04a_numpy_tricks.ipynb
├── chapter_02_pandas_mastery/
│   ├── module_01_dataframes_series/
│   │   └── day_01a_dataframes.ipynb
│   ├── module_02_selection_filtering/
│   │   └── day_02a_selection_filtering.ipynb
│   ├── module_03_groupby_aggregation/
│   │   └── day_03a_groupby_agg.ipynb
│   ├── module_04_merge_join_concat/
│   │   └── day_04a_merge_join.ipynb
│   └── module_05_data_cleaning/
│       └── day_05a_data_cleaning.ipynb
├── chapter_03_ml_algorithms/
│   ├── module_01_linear_regression/
│   │   └── day_01a_linear_regression.ipynb
│   ├── module_02_logistic_regression/
│   │   └── day_02a_logistic_regression.ipynb
│   ├── module_03_svm/
│   │   └── day_03a_svm.ipynb
│   ├── module_04_decision_trees_rf/
│   │   └── day_04a_trees_rf.ipynb
│   └── module_05_knn_naive_bayes/
│       └── day_05a_knn_nb.ipynb
├── chapter_04_sklearn_practice/
│   ├── module_01_preprocessing/
│   │   └── day_01a_preprocessing.ipynb
│   ├── module_02_feature_engineering/
│   │   └── day_02a_feature_engineering.ipynb
│   ├── module_03_model_selection/
│   │   └── day_03a_model_selection.ipynb
│   └── module_04_pipelines/
│       └── day_04a_sklearn_pipelines.ipynb
├── chapter_05_dl_fundamentals/
│   ├── module_01_neural_network_math/
│   │   └── day_01a_nn_math.ipynb
│   ├── module_02_backprop/
│   │   └── day_02a_backpropagation.ipynb
│   ├── module_03_activations_loss/
│   │   └── day_03a_activations_loss.ipynb
│   └── module_04_optimizers_regularization/
│       └── day_04a_optimizers_reg.ipynb
├── chapter_06_pytorch/
│   ├── module_01_tensors_autograd/
│   │   └── day_01a_tensors_autograd.ipynb
│   ├── module_02_nn_module/
│   │   └── day_02a_nn_module.ipynb
│   ├── module_03_training_loop/
│   │   └── day_03a_training_loop.ipynb
│   ├── module_04_cnn_from_scratch/
│   │   └── day_04a_cnn_pytorch.ipynb
│   └── module_05_rnn_lstm/
│       └── day_05a_rnn_lstm_pytorch.ipynb
└── chapter_07_tensorflow_keras/
    ├── module_01_tf_basics/
    │   └── day_01a_tf_basics.ipynb
    ├── module_02_keras_sequential/
    │   └── day_02a_keras_sequential.ipynb
    ├── module_03_functional_api/
    │   └── day_03a_functional_api.ipynb
    ├── module_04_tf_data/
    │   └── day_04a_tf_data_pipeline.ipynb
    └── module_05_transfer_learning/
        └── day_05a_transfer_learning.ipynb
```

---

## 📋 Detailed Content Plan

---

### 1️⃣ OS-Quick-Prep-Notes (18 Notebooks)

#### Chapter 01: Process Management

| Module | Notebook                       | Content Details                                                                                                                                                                                                                                                                                                          |
| ------ | ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 01     | `day_01a_processes.ipynb`      | What is a process, process states (new→ready→running→waiting→terminated), PCB structure, context switching, process creation (fork/exec), zombie & orphan processes. **Code:** Python `multiprocessing` module demo, `os.fork()` on Linux. **Interview Qs:** fork() output puzzles, zombie vs orphan, process vs program |
| 02     | `day_02a_threads.ipynb`        | Thread vs process, user vs kernel threads, multithreading models (many-to-one, one-to-one, many-to-many), benefits & challenges. **Code:** Python `threading` module, GIL explanation, thread creation/joining. **Interview Qs:** Thread vs process, GIL, when to use threads vs processes                               |
| 03     | `day_03a_cpu_scheduling.ipynb` | FCFS, SJF, SRTF, Round Robin, Priority Scheduling, Multilevel Queue, Multilevel Feedback Queue. Gantt charts, turnaround time, waiting time calculations. **Code:** Python simulation of each algorithm with step traces. **Interview Qs:** Compare algorithms, starvation, convoy effect                                |
| 04     | `day_04a_ipc.ipynb`            | Shared memory, message passing, pipes (named/unnamed), sockets, signals. **Code:** Python `multiprocessing.Pipe`, `Queue`, shared memory examples. **Interview Qs:** IPC mechanisms comparison, when to use what                                                                                                         |

#### Chapter 02: Synchronization

| Module | Notebook                              | Content Details                                                                                                                                                                                                                                                                               |
| ------ | ------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 01     | `day_01a_critical_section.ipynb`      | Race conditions, critical section problem, requirements (mutual exclusion, progress, bounded waiting), Peterson's solution, hardware solutions (test-and-set, compare-and-swap). **Code:** Race condition demo with threads, lock usage. **Interview Qs:** What is race condition, Peterson's |
| 02     | `day_02a_mutex_semaphore.ipynb`       | Mutex vs semaphore (binary vs counting), spinlock, monitor, condition variables. **Code:** Python `threading.Lock`, `Semaphore`, `Condition` with examples. **Interview Qs:** Mutex vs semaphore, binary semaphore vs mutex                                                                   |
| 03     | `day_03a_classic_sync_problems.ipynb` | Producer-Consumer, Readers-Writers, Dining Philosophers. Full solutions with semaphores and mutexes. **Code:** Complete Python implementations of all three. **Interview Qs:** Solve these problems, identify potential issues                                                                |
| 04     | `day_04a_deadlocks.ipynb`             | Deadlock conditions (Coffman), detection (wait-for graph, RAG), prevention, avoidance (Banker's algorithm), recovery. **Code:** Banker's algorithm implementation, deadlock detection. **Interview Qs:** Deadlock scenarios, prevention vs avoidance                                          |

#### Chapter 03: Memory Management

| Module | Notebook                         | Content Details                                                                                                                                                                                                                          |
| ------ | -------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 01     | `day_01a_memory_basics.ipynb`    | Contiguous allocation, fragmentation (internal/external), compaction, memory allocation strategies (first-fit, best-fit, worst-fit). **Code:** Simulation of allocation strategies. **Interview Qs:** Internal vs external fragmentation |
| 02     | `day_02a_paging.ipynb`           | Paging concept, page table, TLB, multi-level paging, inverted page table, address translation walkthrough. **Code:** Address translation calculator, page table simulator. **Interview Qs:** Page table entries, TLB miss handling       |
| 03     | `day_03a_virtual_memory.ipynb`   | Virtual memory concept, demand paging, page fault handling, copy-on-write, memory-mapped files, thrashing. **Code:** Page fault simulation. **Interview Qs:** What causes thrashing, working set model                                   |
| 04     | `day_04a_page_replacement.ipynb` | FIFO, LRU, Optimal, Clock (Second Chance), LFU. Belady's anomaly. **Code:** Complete implementation of each algorithm with step traces. **Interview Qs:** Compare algorithms, Belady's anomaly                                           |

#### Chapter 04: File Systems

| Module | Notebook                          | Content Details                                                                                                                                                                                  |
| ------ | --------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 01     | `day_01a_file_organization.ipynb` | File allocation methods (contiguous, linked, indexed), FAT, inode structure, directory implementations. **Code:** Inode structure visualization. **Interview Qs:** Compare allocation methods    |
| 02     | `day_02a_disk_scheduling.ipynb`   | FCFS, SSTF, SCAN, C-SCAN, LOOK, C-LOOK algorithms. Seek time calculations. **Code:** Python simulation with visualization of head movement. **Interview Qs:** Compare disk scheduling algorithms |
| 03     | `day_03a_io_systems.ipynb`        | I/O hardware, polling vs interrupts, DMA, buffering strategies, RAID levels (0,1,5,10). **Code:** RAID capacity/speed calculations. **Interview Qs:** RAID comparison, DMA advantages            |

#### Chapter 05: Linux Essentials

| Module | Notebook                         | Content Details                                                                                                                                                                        |
| ------ | -------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 01     | `day_01a_process_commands.ipynb` | ps, top, htop, kill, nice, fg/bg, nohup, cron, systemd. Process management in practice. **Code:** Command examples with output. **Interview Qs:** Kill signals, zombie process cleanup |
| 02     | `day_02a_file_permissions.ipynb` | chmod, chown, umask, setuid/setgid, sticky bit, ACLs. **Code:** Permission calculation examples. **Interview Qs:** Permission scenarios, 777 vs 755                                    |
| 03     | `day_03a_shell_scripting.ipynb`  | Variables, conditionals, loops, functions, pipes, grep/sed/awk basics, common one-liners. **Code:** Practical shell scripts. **Interview Qs:** Write a script to..., pipe puzzles      |

---

### 2️⃣ DBMS-Quick-Prep-Notes (20 Notebooks)

#### Chapter 01: Fundamentals

| Module | Notebook                         | Content Details                                                                                                                                                                                        |
| ------ | -------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 01     | `day_01a_rdbms_basics.ipynb`     | DBMS vs RDBMS, schema, instances, 3-level architecture (external/conceptual/internal), data independence. **Interview Qs:** DBMS vs file system, data independence                                     |
| 02     | `day_02a_er_model.ipynb`         | Entities, attributes, relationships, cardinality (1:1, 1:N, M:N), weak entities, ER to relational mapping. **Code:** ASCII ER diagrams. **Interview Qs:** Design ER for scenarios                      |
| 03     | `day_03a_keys_constraints.ipynb` | Super key, candidate key, primary key, foreign key, composite key, unique, NOT NULL, CHECK, referential integrity. **Code:** SQL DDL for each constraint. **Interview Qs:** Identify keys in scenarios |
| 04     | `day_04a_normalization.ipynb`    | 1NF, 2NF, 3NF, BCNF, 4NF. Functional dependencies, closures, decomposition (lossless, dependency-preserving). Step-by-step normalization examples. **Interview Qs:** Normalize a given table           |

#### Chapter 02: SQL Mastery

| Module | Notebook                         | Content Details                                                                                                                                                                                                      |
| ------ | -------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 01     | `day_01a_select_basics.ipynb`    | SELECT, WHERE, ORDER BY, LIMIT, DISTINCT, LIKE, IN, BETWEEN, IS NULL, CASE WHEN. **Code:** 10+ practice queries on sample data. **Focus:** Write from memory                                                         |
| 02     | `day_02a_joins.ipynb`            | INNER, LEFT, RIGHT, FULL OUTER, CROSS, SELF JOIN. Venn diagrams in ASCII. **Code:** Each join type with examples and edge cases. **Interview Qs:** Join puzzles                                                      |
| 03     | `day_03a_subqueries_ctes.ipynb`  | Scalar, row, table subqueries, correlated subqueries, EXISTS, NOT EXISTS, WITH (CTEs), recursive CTEs. **Code:** Complex nested queries. **Interview Qs:** Rewrite subquery as join                                  |
| 04     | `day_04a_window_functions.ipynb` | ROW_NUMBER, RANK, DENSE_RANK, NTILE, LAG, LEAD, FIRST_VALUE, LAST_VALUE, SUM/AVG OVER(). PARTITION BY + ORDER BY. **Code:** Real interview window function problems. **Focus:** These come up in EVERY SQL interview |
| 05     | `day_05a_sql_practice.ipynb`     | 15-20 SQL interview problems of increasing difficulty. Employee-Department-Salary scenarios, rank within groups, running totals, gaps and islands, duplicates. **Code:** Problem + solution + explanation for each   |

#### Chapter 03: Transactions

| Module | Notebook                            | Content Details                                                                                                                                                                                                     |
| ------ | ----------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 01     | `day_01a_acid.ipynb`                | Atomicity, Consistency, Isolation, Durability — what each means with real examples, WAL (write-ahead logging), undo/redo logs. **Interview Qs:** Explain each property with example                                 |
| 02     | `day_02a_concurrency_control.ipynb` | Lost update, dirty read, non-repeatable read, phantom read. Lock-based (2PL strict/rigorous), timestamp-based, MVCC. **Code:** Scenario traces. **Interview Qs:** Identify anomalies                                |
| 03     | `day_03a_isolation_levels.ipynb`    | Read Uncommitted, Read Committed, Repeatable Read, Serializable. Which prevents what. PostgreSQL vs MySQL defaults. **Code:** Table showing level vs anomaly. **Interview Qs:** Choose isolation level for scenario |
| 04     | `day_04a_deadlocks_recovery.ipynb`  | Deadlock in DBMS, wait-for graph, timeout, wound-wait, wait-die. Recovery: log-based, checkpoint, shadow paging. **Interview Qs:** Deadlock handling in databases                                                   |

#### Chapter 04: Indexing & Optimization

| Module | Notebook                           | Content Details                                                                                                                                                                                        |
| ------ | ---------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 01     | `day_01a_btree_indexing.ipynb`     | B-tree vs B+ tree (structure, properties, search, insert, delete), clustered vs non-clustered index, dense vs sparse. **Code:** B+ tree search simulation. **Interview Qs:** Why B+ tree for databases |
| 02     | `day_02a_hash_indexing.ipynb`      | Static vs dynamic hashing, extendible hashing, linear hashing, bitmap indexing. **Code:** Hash index lookup simulation. **Interview Qs:** Hash vs B+ tree index                                        |
| 03     | `day_03a_query_optimization.ipynb` | Query execution plans, EXPLAIN output reading, index selection, query rewriting, join order optimization. **Code:** EXPLAIN examples, slow query optimization. **Interview Qs:** Optimize given query  |

#### Chapter 05: Advanced Topics

| Module | Notebook                             | Content Details                                                                                                                                                                          |
| ------ | ------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 01     | `day_01a_nosql.ipynb`                | Types (key-value, document, column-family, graph), MongoDB, Redis, Cassandra basics, when to use NoSQL. **Interview Qs:** SQL vs NoSQL, choose DB for scenario                           |
| 02     | `day_02a_cap_theorem.ipynb`          | CAP theorem, PACELC, consistency models (strong/eventual/causal), real-world examples (DynamoDB=AP, MongoDB=CP). **Interview Qs:** Explain CAP with examples                             |
| 03     | `day_03a_sharding_replication.ipynb` | Horizontal vs vertical partitioning, sharding strategies (hash, range, directory), replication (master-slave, multi-master), consistency. **Interview Qs:** Design sharding for scenario |

---

### 3️⃣ CN-Quick-Prep-Notes (16 Notebooks)

#### Chapter 01: Network Models

| Module | Notebook                      | Content Details                                                                                                                                                                                   |
| ------ | ----------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 01     | `day_01a_osi_model.ipynb`     | 7 layers deep dive — what each layer does, protocols at each layer, PDU names, devices at each layer. ASCII art layered diagram. **Interview Qs:** Which layer does X, arrange protocols by layer |
| 02     | `day_02a_tcp_ip_model.ipynb`  | 4-layer model, comparison with OSI, why TCP/IP won, real-world protocol mapping. **Interview Qs:** OSI vs TCP/IP differences                                                                      |
| 03     | `day_03a_encapsulation.ipynb` | Data encapsulation/decapsulation, headers at each layer, packet frame segment, MTU, fragmentation. **Code:** Packet structure visualization. **Interview Qs:** Trace a packet through layers      |

#### Chapter 02: Application Layer

| Module | Notebook                        | Content Details                                                                                                                                                                                                  |
| ------ | ------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 01     | `day_01a_http_https.ipynb`      | HTTP/1.1 vs HTTP/2 vs HTTP/3, methods, headers, status codes, cookies, sessions, HTTPS = HTTP + TLS. **Code:** Python requests examples. **Interview Qs:** GET vs POST, 301 vs 302                               |
| 02     | `day_02a_dns.ipynb`             | DNS hierarchy, resolution process (recursive vs iterative), DNS record types (A, AAAA, CNAME, MX, NS), DNS caching, TTL. **Code:** `nslookup`/`dig` simulation. **Interview Qs:** What happens when you type URL |
| 03     | `day_03a_email_protocols.ipynb` | SMTP, POP3, IMAP — how email works end-to-end, port numbers, differences. **Interview Qs:** SMPT vs POP3 vs IMAP                                                                                                 |
| 04     | `day_04a_rest_websocket.ipynb`  | REST constraints, RESTful API design, WebSocket vs HTTP, Server-Sent Events, long polling, gRPC basics. **Interview Qs:** When to use WebSocket vs REST                                                          |

#### Chapter 03: Transport Layer

| Module | Notebook                        | Content Details                                                                                                                                                                                                                                             |
| ------ | ------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 01     | `day_01a_tcp.ipynb`             | 3-way handshake (SYN/SYN-ACK/ACK), 4-way termination, TCP header fields, sequence numbers, ACKs, retransmission, connection states (LISTEN, ESTABLISHED, TIME_WAIT). **Code:** TCP state machine simulation. **Interview Qs:** Explain handshake, TIME_WAIT |
| 02     | `day_02a_udp.ipynb`             | UDP header (8 bytes), connectionless, no reliability, checksum, use cases (DNS, video streaming, gaming). TCP vs UDP comparison table. **Interview Qs:** When to use UDP                                                                                    |
| 03     | `day_03a_flow_congestion.ipynb` | Flow control (sliding window), congestion control (slow start, congestion avoidance, fast retransmit, fast recovery), AIMD. **Code:** Window size simulation. **Interview Qs:** Slow start vs congestion avoidance                                          |

#### Chapter 04: Network Layer

| Module | Notebook                      | Content Details                                                                                                                                                                              |
| ------ | ----------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 01     | `day_01a_ip_addressing.ipynb` | IPv4 structure, classes (A/B/C/D/E), private vs public IP, special addresses, CIDR notation. **Code:** IP class identifier. **Interview Qs:** Identify class, number of hosts                |
| 02     | `day_02a_subnetting.ipynb`    | Subnet masks, CIDR, subnet calculation (network address, broadcast, host range), VLSM, supernetting. **Code:** Subnet calculator in Python. **Interview Qs:** Given IP/mask, find network    |
| 03     | `day_03a_routing.ipynb`       | Static vs dynamic routing, distance vector (RIP, Bellman-Ford), link state (OSPF, Dijkstra), path vector (BGP), AS. **Code:** Bellman-Ford routing simulation. **Interview Qs:** RIP vs OSPF |
| 04     | `day_04a_nat_ipv6.ipynb`      | NAT types (static, dynamic, PAT/NAPT), NAT traversal, IPv6 addressing, IPv4→IPv6 transition. **Interview Qs:** Why NAT, IPv4 exhaustion                                                      |

#### Chapter 05: Security

| Module | Notebook                       | Content Details                                                                                                                                                                                                                           |
| ------ | ------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 01     | `day_01a_ssl_tls.ipynb`        | SSL/TLS handshake step-by-step, certificates, certificate authorities, certificate chain, HTTPS setup. **Code:** TLS handshake trace. **Interview Qs:** Explain TLS handshake                                                             |
| 02     | `day_02a_encryption_vpn.ipynb` | Symmetric (AES, DES) vs asymmetric (RSA), hashing (SHA, MD5), digital signatures, VPN (IPSec, SSL VPN), firewalls (packet filter, stateful, proxy). **Code:** Python hashlib, basic encryption. **Interview Qs:** Symmetric vs asymmetric |

---

### 4️⃣ OOP-Design-Patterns-Quick-Prep-Notes (20 Notebooks)

#### Chapter 01: OOP Fundamentals (Python)

| Module | Notebook                                  | Content Details                                                                                                                                                                                               |
| ------ | ----------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 01     | `day_01a_classes_objects.ipynb`           | Classes, objects, `__init__`, instance vs class variables, `self`, `__str__`/`__repr__`, `__eq__`, dunder methods. **Code:** Build a complete class from scratch. **Interview:** Implement a class for...     |
| 02     | `day_02a_encapsulation_abstraction.ipynb` | Public/protected/private (`_`, `__`), property decorators, getters/setters, ABC module, abstract methods. **Code:** Encapsulated class with validation. **Interview:** Why encapsulation matters              |
| 03     | `day_03a_inheritance.ipynb`               | Single, multiple, multilevel, hierarchical, MRO (C3 linearization), `super()`, diamond problem, mixins. **Code:** Each type with examples. **Interview:** Diamond problem, MRO                                |
| 04     | `day_04a_polymorphism.ipynb`              | Method overriding, operator overloading, duck typing, runtime vs compile-time polymorphism, Protocol class (structural typing). **Code:** Polymorphic designs. **Interview:** Types of polymorphism in Python |

#### Chapter 02: SOLID Principles

| Module | Notebook                | Content Details                                                                                                                                                                                                      |
| ------ | ----------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 01     | `day_01a_srp_ocp.ipynb` | SRP: one reason to change — bad vs good examples. OCP: open for extension, closed for modification — strategy pattern. **Code:** Refactor violating code to follow SRP/OCP. **Interview:** Identify SOLID violations |
| 02     | `day_02a_lsp_isp.ipynb` | LSP: subtypes substitutable — Rectangle/Square problem. ISP: no client forced to depend on unused methods. **Code:** Fix LSP violation, split fat interfaces. **Interview:** LSP violation examples                  |
| 03     | `day_03a_dip.ipynb`     | Depend on abstractions not concretions. Dependency injection in Python. **Code:** Refactor tightly coupled code. **Interview:** DI vs DIP                                                                            |

#### Chapter 03: Creational Patterns

| Module | Notebook                                 | Content Details                                                                                                                                                                                                              |
| ------ | ---------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 01     | `day_01a_singleton_factory.ipynb`        | Singleton: thread-safe, module-level, metaclass approaches. Factory Method: creator + product hierarchy. **Code:** All implementations in Python. **Interview:** When to use each, singleton downsides                       |
| 02     | `day_02a_abstract_factory_builder.ipynb` | Abstract Factory: family of related objects. Builder: step-by-step complex object construction, fluent interface. **Code:** GUI theme factory, complex config builder. **Interview:** Factory vs Abstract Factory vs Builder |
| 03     | `day_03a_prototype.ipynb`                | Prototype: `copy`/`deepcopy`, registry pattern, when to clone vs construct. **Code:** Prototype with Python copy module. **Interview:** Deep vs shallow copy                                                                 |

#### Chapter 04: Structural Patterns

| Module | Notebook                            | Content Details                                                                                                                                                                                              |
| ------ | ----------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 01     | `day_01a_adapter_decorator.ipynb`   | Adapter: incompatible interface wrapper. Decorator: add behavior dynamically (Python decorators vs GoF decorator). **Code:** Both patterns in Python. **Interview:** Adapter vs Facade, Python decorator use |
| 02     | `day_02a_facade_proxy.ipynb`        | Facade: simplified interface to subsystem. Proxy: virtual, protection, remote proxy. **Code:** Subsystem facade, lazy-loading proxy. **Interview:** Types of proxy                                           |
| 03     | `day_03a_composite_flyweight.ipynb` | Composite: tree of objects (file system). Flyweight: shared state for memory optimization (text editor). **Code:** File system composite, character flyweight. **Interview:** When to use composite          |

#### Chapter 05: Behavioral Patterns

| Module | Notebook                          | Content Details                                                                                                                                                                                        |
| ------ | --------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 01     | `day_01a_observer_strategy.ipynb` | Observer: publisher-subscriber, event handling. Strategy: interchangeable algorithms. **Code:** Event system, sorting strategy. **Interview:** Observer vs pub-sub                                     |
| 02     | `day_02a_command_state.ipynb`     | Command: encapsulate request as object (undo/redo). State: behavior changes with internal state (vending machine). **Code:** Command with undo, state machine. **Interview:** Command pattern benefits |
| 03     | `day_03a_template_iterator.ipynb` | Template Method: algorithm skeleton, defer steps. Iterator: sequential access without exposing structure. **Code:** Data parser template, custom iterator. **Interview:** Template vs strategy         |
| 04     | `day_04a_chain_mediator.ipynb`    | Chain of Responsibility: chain handlers (middleware). Mediator: centralized communication (chat room). **Code:** Request pipeline, mediator. **Interview:** When to use chain vs mediator              |

---

### 5️⃣ System-Design-Quick-Prep-Notes (22 Notebooks)

#### Chapter 01: Fundamentals

| Module | Notebook                           | Content Details                                                                                                                                                                        |
| ------ | ---------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 01     | `day_01a_scalability.ipynb`        | Horizontal vs vertical scaling, stateless services, database scaling, microservices vs monolith. With ASCII architecture diagrams. **Interview:** Scale a system from 100 to 1M users  |
| 02     | `day_02a_cap_consistency.ipynb`    | CAP theorem deep dive, consistency models (strong, eventual, causal, read-your-writes), real-world trade-offs. **Interview:** Your system needs consistency — what do you sacrifice?   |
| 03     | `day_03a_latency_throughput.ipynb` | Latency numbers every programmer should know, throughput calculations, P99 latency, SLAs. **Interview:** Optimize for low latency vs high throughput                                   |
| 04     | `day_04a_back_of_envelope.ipynb`   | QPS estimation, storage estimation, bandwidth estimation, memory estimation. Framework for calculations. **Code:** Calculator templates. **Interview:** Estimate storage for Instagram |

#### Chapter 02: Building Blocks

| Module | Notebook                         | Content Details                                                                                                                                                                                 |
| ------ | -------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 01     | `day_01a_lb_cdn.ipynb`           | Load balancer types (L4/L7), algorithms (round robin, weighted, least connections, IP hash), CDN edge caching, push vs pull CDN. **Interview:** Choose LB algorithm for scenario                |
| 02     | `day_02a_caching.ipynb`          | Cache-aside, write-through, write-behind, read-through. Redis/Memcached, cache invalidation, eviction policies, cache stampede, thundering herd. **Interview:** Design caching strategy for app |
| 03     | `day_03a_database_choices.ipynb` | SQL vs NoSQL decision framework, database per service, read replicas, write master, connection pooling, database indexing strategy. **Interview:** Choose database for use case                 |
| 04     | `day_04a_message_queues.ipynb`   | Kafka, RabbitMQ, SQS — architecture, producers/consumers, pub/sub, event-driven architecture, exactly-once delivery. **Interview:** When to use message queue                                   |
| 05     | `day_05a_api_gateway.ipynb`      | API gateway pattern, reverse proxy, rate limiting, circuit breaker, service mesh, service discovery. **Interview:** Why API gateway                                                             |

#### Chapter 03: Low-Level Design (LLD)

| Module | Notebook                         | Content Details                                                                                                                                                                             |
| ------ | -------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 01     | `day_01a_parking_lot.ipynb`      | Requirements, class diagram, Vehicle/Spot/ParkingLot classes, payment system, entry/exit. **Code:** Complete Python OOP implementation. **Interview:** Design a parking lot system          |
| 02     | `day_02a_lru_cache_design.ipynb` | LRU Cache with OrderedDict and from scratch (HashMap + Doubly Linked List), thread safety. **Code:** Both implementations. **Interview:** Implement LRU cache (LC #146 + design version)    |
| 03     | `day_03a_rate_limiter.ipynb`     | Token bucket, leaky bucket, fixed window, sliding window log, sliding window counter. **Code:** Each algorithm implementation. **Interview:** Design rate limiter for API                   |
| 04     | `day_04a_elevator.ipynb`         | Requirements, state machine, scheduling algorithms (SCAN, LOOK), class design (Elevator, ElevatorSystem, Request). **Code:** Complete implementation. **Interview:** Design elevator system |
| 05     | `day_05a_booking_system.ipynb`   | Seat selection, concurrency handling (optimistic locking), payment flow, class design. **Code:** BookMyShow-style booking system. **Interview:** Design ticket booking system               |
| 06     | `day_06a_snake_game.ipynb`       | Grid, snake movement, food generation, collision detection, game loop. **Code:** Complete terminal game. **Interview:** Design Snake game                                                   |

#### Chapter 04: High-Level Design (HLD)

| Module | Notebook                        | Content Details                                                                                                                                                   |
| ------ | ------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 01     | `day_01a_url_shortener.ipynb`   | Encoding algorithms (base62, MD5), database schema, read-heavy optimization, 301 vs 302, analytics. ASCII architecture diagram. **Interview:** Design TinyURL     |
| 02     | `day_02a_twitter.ipynb`         | Tweet storage, timeline generation (fan-out on write vs read), follow graph, trending, search. **Interview:** Design Twitter's news feed                          |
| 03     | `day_03a_instagram.ipynb`       | Photo upload/storage (S3 + CDN), feed generation, user timeline, stories, explore page. **Interview:** Design Instagram                                           |
| 04     | `day_04a_whatsapp.ipynb`        | WebSocket connections, message delivery (sent/delivered/read), group messaging, message storage, end-to-end encryption. **Interview:** Design WhatsApp            |
| 05     | `day_05a_netflix_youtube.ipynb` | Video upload pipeline (transcoding), adaptive bitrate streaming (HLS/DASH), recommendation engine placement, CDN for video. **Interview:** Design YouTube/Netflix |
| 06     | `day_06a_uber.ipynb`            | Location tracking, matching algorithm, ETA calculation, surge pricing, map partitioning (geohash/quadtree). **Interview:** Design Uber                            |

#### Chapter 05: Interview Framework

| Module | Notebook                               | Content Details                                                                                                                                                                                         |
| ------ | -------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 01     | `day_01a_sd_interview_framework.ipynb` | RESHADED framework, 4-step approach (requirements → estimation → design → deep dive), how to drive the conversation, common mistakes, template for any design question. **Interview:** General approach |

---

### 6️⃣ Backend-FastAPI-Quick-Prep-Notes (22 Notebooks)

#### Chapter 01: Web Fundamentals

| Module | Notebook                            | Content Details                                                                                                                                                                                         |
| ------ | ----------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 01     | `day_01a_http_methods_status.ipynb` | HTTP methods (GET/POST/PUT/PATCH/DELETE), idempotency, status codes (2xx/3xx/4xx/5xx), headers, content types. **Code:** Python requests library examples. **Focus:** Know every status code            |
| 02     | `day_02a_rest_api_design.ipynb`     | REST constraints, resource naming, URL structure, versioning, pagination, filtering, HATEOAS. **Code:** Design a REST API for a blog. **Interview:** Design API for...                                  |
| 03     | `day_03a_wsgi_asgi.ipynb`           | WSGI (synchronous) vs ASGI (asynchronous), Gunicorn, Uvicorn, how Python web servers work under the hood. **Code:** Minimal WSGI/ASGI app from scratch. **Interview:** Why ASGI for FastAPI             |
| 04     | `day_04a_api_best_practices.ipynb`  | Error handling patterns, rate limiting, pagination (cursor vs offset), versioning strategies, API documentation (OpenAPI). **Code:** Best practices implementation. **Interview:** API design decisions |

#### Chapter 02: FastAPI Core

| Module | Notebook                             | Content Details                                                                                                                                                                                  |
| ------ | ------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 01     | `day_01a_hello_fastapi.ipynb`        | FastAPI setup, first endpoint, automatic docs (/docs, /redoc), async basics, project structure. **Code:** Complete hello world API with multiple endpoints                                       |
| 02     | `day_02a_path_query_params.ipynb`    | Path parameters, query parameters, request body, form data, file upload, type validation. **Code:** CRUD API with all param types                                                                |
| 03     | `day_03a_pydantic_validation.ipynb`  | Pydantic models, field validators, model validators, nested models, response models, serialization. **Code:** Complex validation schemas. **Interview:** Why Pydantic                            |
| 04     | `day_04a_dependency_injection.ipynb` | Depends(), sub-dependencies, DB session injection, auth dependency, caching dependencies, yield dependencies. **Code:** Build a DI-based service layer. **Interview:** Explain DI in FastAPI     |
| 05     | `day_05a_middleware_cors.ipynb`      | Custom middleware, CORS configuration, request/response lifecycle, exception handlers, startup/shutdown events. **Code:** Logging middleware, error handler. **Interview:** Middleware use cases |

#### Chapter 03: Database Integration

| Module | Notebook                      | Content Details                                                                                                                                                                        |
| ------ | ----------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 01     | `day_01a_sqlalchemy.ipynb`    | SQLAlchemy ORM setup, models, relationships (1:1, 1:N, M:N), CRUD operations, sessions, eager/lazy loading. **Code:** Complete User-Post-Comment models. **Interview:** ORM vs raw SQL |
| 02     | `day_02a_alembic.ipynb`       | Alembic setup, auto-generate migrations, manual migrations, upgrade/downgrade, migration best practices. **Code:** Full migration workflow                                             |
| 03     | `day_03a_async_db.ipynb`      | async SQLAlchemy, asyncpg, connection pooling, async session management, performance comparison. **Code:** Async CRUD endpoints with DB                                                |
| 04     | `day_04a_mongodb_motor.ipynb` | Motor async MongoDB driver, document modeling, CRUD, aggregation pipeline, indexing. **Code:** FastAPI + MongoDB API. **Interview:** When MongoDB vs PostgreSQL                        |

#### Chapter 04: Auth & Security

| Module | Notebook                           | Content Details                                                                                                                                                                  |
| ------ | ---------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 01     | `day_01a_jwt_auth.ipynb`           | JWT structure (header.payload.signature), access + refresh tokens, token flow, password hashing (bcrypt). **Code:** Complete JWT auth system. **Interview:** JWT vs session auth |
| 02     | `day_02a_oauth2.ipynb`             | OAuth2 flows (auth code, client credentials, PKCE), scopes, FastAPI OAuth2PasswordBearer, social login. **Code:** OAuth2 implementation. **Interview:** OAuth2 flow explanation  |
| 03     | `day_03a_security_practices.ipynb` | CORS, CSRF, XSS prevention, SQL injection prevention, rate limiting, input sanitization, HTTPS. **Code:** Secure FastAPI setup. **Interview:** OWASP Top 10                      |

#### Chapter 05: Async Processing

| Module | Notebook                         | Content Details                                                                                                                                                                                       |
| ------ | -------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 01     | `day_01a_async_await.ipynb`      | Python async/await deep dive, event loop, asyncio, concurrent tasks, `gather()`, `wait()`, sync vs async performance. **Code:** Async patterns from scratch. **Interview:** How async works in Python |
| 02     | `day_02a_celery_redis.ipynb`     | Celery setup, task queues, periodic tasks, result backends, Redis as broker, monitoring with Flower. **Code:** Email queue, report generation. **Interview:** When to use task queues                 |
| 03     | `day_03a_websockets.ipynb`       | WebSocket in FastAPI, connection manager, broadcasting, rooms, authentication for WS. **Code:** Real-time chat server. **Interview:** WebSocket vs polling                                            |
| 04     | `day_04a_background_tasks.ipynb` | FastAPI BackgroundTasks, when to use vs Celery, file processing, notification sending. **Code:** Background task patterns. **Interview:** Background vs async vs Celery                               |

#### Chapter 06: Deployment

| Module | Notebook                       | Content Details                                                                                                                                                           |
| ------ | ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 01     | `day_01a_docker.ipynb`         | Dockerfile for FastAPI, multi-stage builds, layer optimization, .dockerignore, environment variables. **Code:** Production Dockerfile. **Interview:** Docker concepts     |
| 02     | `day_02a_docker_compose.ipynb` | Multi-container setup (API + DB + Redis), volumes, networks, healthchecks, docker-compose.yml. **Code:** Full stack compose file. **Interview:** Docker Compose use cases |
| 03     | `day_03a_cicd_basics.ipynb`    | GitHub Actions for FastAPI, test → build → deploy pipeline, environment secrets, deploy to cloud. **Code:** Complete CI/CD pipeline YAML. **Interview:** CI/CD concepts   |

---

### 7️⃣ ML-DL-Code-Fluency-Notes (28 Notebooks)

> **Focus:** You already know ML/DL. These notebooks are about **fluently writing code from memory** — no AI IDE help, no Google. Every notebook is code-first with "now write this yourself" exercises.

#### Chapter 01: NumPy Mastery — Write It From Memory

| Module | Notebook                     | Content Details                                                                                                                                                                                      |
| ------ | ---------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 01     | `day_01a_numpy_arrays.ipynb` | Array creation (zeros, ones, arange, linspace, random), dtypes, reshape, indexing (fancy, boolean), slicing. **Code:** 20 operations to memorize. **Drill:** Given a task, write the NumPy one-liner |
| 02     | `day_02a_broadcasting.ipynb` | Broadcasting rules (3 rules), vectorized operations, avoiding loops, performance comparison (loops vs vectorized). **Code:** 10 broadcasting puzzles. **Drill:** Predict output, then verify         |
| 03     | `day_03a_linalg.ipynb`       | `np.dot`, `@`, `np.linalg.inv`, `np.linalg.eig`, SVD, matrix decomposition, solving Ax=b. **Code:** Linear algebra from scratch vs NumPy. **Drill:** Implement PCA using NumPy only                  |
| 04     | `day_04a_numpy_tricks.ipynb` | `np.where`, `np.apply_along_axis`, `np.einsum`, stacking/splitting, structured arrays, memory views, `np.vectorize`. **Code:** Advanced patterns. **Drill:** Optimize given loop with NumPy          |

#### Chapter 02: Pandas Mastery — Write It From Memory

| Module | Notebook                            | Content Details                                                                                                                                                                                           |
| ------ | ----------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 01     | `day_01a_dataframes.ipynb`          | DataFrame/Series creation, `.loc`/`.iloc`, dtypes, info(), describe(), value_counts(), set_index, reset_index. **Code:** 15 core operations. **Drill:** Create + manipulate from memory                   |
| 02     | `day_02a_selection_filtering.ipynb` | Boolean indexing, `.query()`, `.isin()`, `.between()`, `.str` accessor, `.dt` accessor, conditional selection. **Code:** 10 filtering challenges. **Drill:** Filter complex conditions in one line        |
| 03     | `day_03a_groupby_agg.ipynb`         | `groupby()`, `agg()`, `transform()`, `apply()`, `pivot_table()`, `crosstab()`, multi-level groupby. **Code:** Real-world aggregation problems. **Drill:** Replicate SQL GROUP BY in Pandas                |
| 04     | `day_04a_merge_join.ipynb`          | `merge()` (inner/left/right/outer), `join()`, `concat()`, indicator column, handling duplicates in joins. **Code:** Complex merge scenarios. **Drill:** Replicate SQL JOINs in Pandas                     |
| 05     | `day_05a_data_cleaning.ipynb`       | Missing values (fillna, dropna, interpolate), duplicates, type conversion, string cleaning, outlier handling, pipe(). **Code:** End-to-end cleaning pipeline. **Drill:** Clean messy dataset from scratch |

#### Chapter 03: ML Algorithms — Math + Code From Scratch

| Module | Notebook                            | Content Details                                                                                                                                                                                                           |
| ------ | ----------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 01     | `day_01a_linear_regression.ipynb`   | Math: cost function (MSE), gradient descent derivation, normal equation. **Code:** Linear regression from scratch (NumPy only) + sklearn comparison. **Drill:** Code gradient descent from memory                         |
| 02     | `day_02a_logistic_regression.ipynb` | Math: sigmoid, cross-entropy loss, gradient derivation. **Code:** Logistic regression from scratch + sklearn. Decision boundary plotting. **Drill:** Implement binary classifier from scratch                             |
| 03     | `day_03a_svm.ipynb`                 | Math: max margin, support vectors, kernel trick (RBF, polynomial), soft margin (C parameter). **Code:** sklearn SVM with different kernels, hyperparameter tuning. **Drill:** Explain when to use which kernel            |
| 04     | `day_04a_trees_rf.ipynb`            | Decision tree: entropy, information gain, Gini impurity, pruning. Random forest: bagging, feature sampling. **Code:** Decision tree from scratch (ID3) + sklearn RF. **Drill:** Calculate information gain by hand + code |
| 05     | `day_05a_knn_nb.ipynb`              | KNN: distance metrics, K selection, weighted KNN. Naive Bayes: Bayes theorem, Gaussian/Multinomial NB. **Code:** Both from scratch + sklearn. **Drill:** Implement KNN classifier from memory                             |

#### Chapter 04: sklearn Practice — Pipeline Fluency

| Module | Notebook                            | Content Details                                                                                                                                                                                                  |
| ------ | ----------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 01     | `day_01a_preprocessing.ipynb`       | StandardScaler, MinMaxScaler, LabelEncoder, OneHotEncoder, OrdinalEncoder, SimpleImputer, KNNImputer. **Code:** Each transformer with fit/transform pattern. **Drill:** Write preprocessing pipeline from memory |
| 02     | `day_02a_feature_engineering.ipynb` | Polynomial features, interaction features, binning, log transform, target encoding, feature selection (mutual info, RFE, L1). **Code:** Feature engineering pipeline. **Drill:** Improve model with features     |
| 03     | `day_03a_model_selection.ipynb`     | train_test_split, cross_val_score, GridSearchCV, RandomizedSearchCV, learning curves, bias-variance tradeoff. **Code:** Full model selection workflow. **Drill:** Select best model for dataset                  |
| 04     | `day_04a_sklearn_pipelines.ipynb`   | Pipeline, ColumnTransformer, make_pipeline, custom transformers, pipeline serialization (joblib). **Code:** Production-ready ML pipeline. **Drill:** Build end-to-end pipeline from memory                       |

#### Chapter 05: Deep Learning Fundamentals — Math + Code

| Module | Notebook                         | Content Details                                                                                                                                                                                             |
| ------ | -------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 01     | `day_01a_nn_math.ipynb`          | Perceptron, multi-layer network, forward pass math, matrix multiplication for layers. **Code:** Neural network forward pass in pure NumPy. **Drill:** Write forward pass from memory                        |
| 02     | `day_02a_backpropagation.ipynb`  | Chain rule, gradient computation, computational graph, backprop algorithm step-by-step. **Code:** Full backprop implementation in NumPy (XOR problem). **Drill:** Derive and code backprop                  |
| 03     | `day_03a_activations_loss.ipynb` | ReLU, sigmoid, tanh, softmax, LeakyReLU, GELU. Loss: MSE, cross-entropy, binary cross-entropy. **Code:** Implement each + gradient. **Drill:** Choose right activation/loss for task                        |
| 04     | `day_04a_optimizers_reg.ipynb`   | SGD, momentum, RMSprop, Adam, learning rate scheduling. Regularization: L1/L2, dropout, batch norm, early stopping. **Code:** Adam from scratch + compare optimizers. **Drill:** Implement Adam from memory |

#### Chapter 06: PyTorch — Build Models From Memory

| Module | Notebook                         | Content Details                                                                                                                                                                                                                    |
| ------ | -------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 01     | `day_01a_tensors_autograd.ipynb` | Tensor creation, operations, GPU transfer, autograd (requires_grad, backward, grad), computational graph, no_grad(). **Code:** Autograd from basic to advanced. **Drill:** Linear regression with autograd only                    |
| 02     | `day_02a_nn_module.ipynb`        | nn.Module, custom layers, nn.Linear, nn.Sequential, parameters(), named_parameters(), model summary. **Code:** Build custom network class. **Drill:** Write nn.Module from scratch                                                 |
| 03     | `day_03a_training_loop.ipynb`    | DataLoader, Dataset, training loop (forward → loss → backward → step → zero_grad), validation loop, saving/loading, training best practices. **Code:** Complete training pipeline. **Drill:** Write full training loop from memory |
| 04     | `day_04a_cnn_pytorch.ipynb`      | Conv2d, MaxPool2d, BatchNorm2d, building CNN architectures (LeNet, mini-VGG), feature maps visualization. **Code:** CNN for MNIST/CIFAR-10 from scratch. **Drill:** Build CNN architecture from memory                             |
| 05     | `day_05a_rnn_lstm_pytorch.ipynb` | nn.RNN, nn.LSTM, nn.GRU, sequence processing, packed sequences, bidirectional, attention basics. **Code:** Text classification with LSTM. **Drill:** Build LSTM model from memory                                                  |

#### Chapter 07: TensorFlow / Keras — Build Models From Memory

| Module | Notebook                          | Content Details                                                                                                                                                                                                |
| ------ | --------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 01     | `day_01a_tf_basics.ipynb`         | tf.Tensor, tf.Variable, tf.constant, GradientTape, eager execution, tf.function, basic ops. **Code:** GradientTape for custom training. **Drill:** Linear regression with GradientTape                         |
| 02     | `day_02a_keras_sequential.ipynb`  | Sequential model, Dense, Conv2D, compile(), fit(), evaluate(), predict(), callbacks (EarlyStopping, ModelCheckpoint). **Code:** MNIST classifier. **Drill:** Build + train Sequential model from memory        |
| 03     | `day_03a_functional_api.ipynb`    | Functional API for multi-input/output models, skip connections, shared layers, model subclassing. **Code:** ResNet-like block, multi-input model. **Drill:** Build functional model from scratch               |
| 04     | `day_04a_tf_data_pipeline.ipynb`  | tf.data.Dataset, from_tensor_slices, map, batch, shuffle, prefetch, cache, TFRecord. **Code:** Efficient data pipeline. **Drill:** Build input pipeline from memory                                            |
| 05     | `day_05a_transfer_learning.ipynb` | Pre-trained models (MobileNet, ResNet, BERT), feature extraction vs fine-tuning, freezing layers, fine-tuning schedule. **Code:** Transfer learning for custom dataset. **Drill:** Fine-tune model from memory |

---

## 🚀 Execution Order

| Phase | Subject               | Est. Notebooks | Priority             |
| ----- | --------------------- | -------------- | -------------------- |
| 1     | OS Quick Prep         | 18             | Core CS              |
| 2     | DBMS & SQL            | 20             | Core CS              |
| 3     | Computer Networks     | 16             | Core CS              |
| 4     | OOP & Design Patterns | 20             | Core CS              |
| 5     | System Design         | 22             | High Interview Value |
| 6     | Backend FastAPI       | 22             | Practical Skills     |
| 7     | ML/DL Code Fluency    | 28             | Code Confidence      |

---

## 📐 Notebook Template (Every Notebook Follows This)

```
1. 📌 Title + Hook (analogy or real-world scenario)
2. ╔═╗ Concept Box (core theory with ASCII art)
3. 💻 Code / Problems (progressive, explained line-by-line)
4. 🗺️ Pattern Map (╔══╗ format — quick reference)
5. 📝 Practice Problems Table (| # | Problem | Difficulty |)
6. ┌─┐ Key Takeaways Box (interview-ready bullet points)
7. ⏭️ Next Up (link to next module)
```

---

## 📊 Grand Total: ~146 notebooks across 7 subjects

**Let's build.** 🚀
