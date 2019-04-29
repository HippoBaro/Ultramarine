---
title: API index
layout: default
has_children: true
permalink: /api
nav_order: 99
---

# Project index

  - [`ULTRAMARINE_DEFINE_ACTOR`](doc_ultramarine__macro.md#standardese-ULTRAMARINE_DEFINE_ACTOR) - Expands with enclosing actor internal definitions

  - ## Namespace `ultramarine`
    
      - [`ActorKind`](doc_ultramarine__actor_traits.md#standardese-ultramarine__actor_type) - Enum representing the possible kinds of actor
    
      - [`actor`](doc_ultramarine__actor.md#standardese-ultramarine__actor) - Base template class defining an actor
    
      - [`actor_id`](doc_ultramarine__directory.md#standardese-ultramarine__actor_id) - Actors are fetched internally via an unsigned integer id
    
      - [`actor_kind`](doc_ultramarine__actor_traits.md#standardese-ultramarine__actor_kind-Actor---) - Get the actor type
    
      - [`actor_ref`](doc_ultramarine__actor_ref.md#standardese-ultramarine__actor_ref-Actor-) - A movable and copyable reference to a virtual actor
    
      - [`default_local_placement_strategy`](doc_ultramarine__directory.md#standardese-ultramarine__default_local_placement_strategy) - Default local placement strategy uses round\_robin\_local\_placement\_strategy
    
      - [`get`](doc_ultramarine__actor_ref.md#standardese-ultramarine__get-Actor-KeyType--KeyType---) - Create a reference to a virtual actor
    
      - [`is_local_actor_v`](doc_ultramarine__actor_traits.md#standardese-ultramarine__is_local_actor_v) - Compile-time trait returning true if actor type is local
    
      - [`is_reentrant_v`](doc_ultramarine__actor_traits.md#standardese-ultramarine__is_reentrant_v) - Compile-time trait returning true if the actor type is reentrant
    
      - [`is_unlimited_concurrent_local_actor_v`](doc_ultramarine__actor_traits.md#standardese-ultramarine__is_unlimited_concurrent_local_actor_v) - Compile-time trait returning true if the local actor type doesn’t specify a concurrency limit
    
      - [`local_actor`](doc_ultramarine__actor_attributes.md#standardese-ultramarine__local_actor) - Actor attribute base class that specify that the Derived actor should be treated as a local actor
    
      - [`message_buffer`](doc_ultramarine__utility.md#standardese-ultramarine__message_buffer-Future-) - A dynamic message buffer storing a set number of futures running concurrently
    
      - [`non_reentrant_actor`](doc_ultramarine__actor_attributes.md#standardese-ultramarine__non_reentrant_actor) - Actor attribute base class that specify that the Derived actor should be protected against reentrancy
    
      - [`round_robin_local_placement_strategy`](doc_ultramarine__directory.md#standardese-ultramarine__round_robin_local_placement_strategy) - A round-robin placement strategy that shards actors based on the modulo of their hashed key
    
      - [`with_buffer`](doc_ultramarine__utility.md#standardese-ultramarine__with_buffer-Func--std__size_t-Func---) - Create a dynamic message buffer to use in a specified function scope
