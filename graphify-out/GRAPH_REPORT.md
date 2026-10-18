# Graph Report - Fable-2-Recomp  (2026-10-18)

## Corpus Check
- 178 files · ~292,033 words
- Verdict: corpus is large enough that graph structure adds value.
- Unclassified: 42 file(s) not represented in the graph (top: .cmd 19, (none) 8, .patch 6)

## Summary
- 3027 nodes · 5189 edges · 153 communities (125 shown, 28 thin omitted)
- Extraction: 98% EXTRACTED · 2% INFERRED · 0% AMBIGUOUS · INFERRED: 127 edges (avg confidence: 0.86)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `d8aeded8`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- xex_verify.h
- fable2_ui_input_probe.h
- fable2_state_probe.h
- VkFns
- GamepadDriver
- Fable2ConfigValues
- fable2_modmenu.h
- VulkanApp
- fable2_av_probe.h
- fable2_text_append.h
- fable_2_pch
- remote_control_server.h
- Value
- ControlServer
- Fable2ConfigFile
- Window
- Hero dog targeted readback plan
- X360Disc
- KeyboardGamepadDriver
- RoutedEventArgs
- Idx
- ExtractionProgress
- sys
- fable2_patches.h
- fable2_deadbeef.h
- cstdint
- fable2_patches.cpp
- fable2_func_trace.h
- fable2_ui_render_probe.h
- MainWindow.xaml.cs
- J. Unnamed Body Functions
- I. Trampolines & Getters
- subprocess
- F5.lua
- fps_probe.h
- CallActivePlayerMethod_821A11E8.cpp
- MainWindow
- H. Switch / Jump-Table Dispatchers
- fable2_glyph_probe.h
- struct
- .Classify
- IsoImage
- Parser
- chest_siblings.txt 8-sibling item-op dispatch script
- .Init
- RuntimeStagingTests
- fable2_modmenu.h mod menu module
- Interval
- Parte A — T3: teselación continua emulada en el vertex shader
- clean_pe.py
- argparse
- Values
- X360Disc facade
- StfsContainer
- cstdio
- fable2_stall_dump.h
- fable2_launcher.py
- LauncherViewModel
- context
- ProcessGameFrame_82276C30 hand-tuned override
- cstring
- fable_2_app.h
- mouse_look.h
- Tareas
- G. Virtual-Dispatch Thunks (vtable)
- fable2_ui_text_dump.h
- gaddr
- gdfx_extract.py
- X360Extract.Core.csproj
- chrono
- RemoteControlServer
- ProcessGameFrame_82276C30.cpp
- .CreateRenderPassAndCommands
- Fable 2 ReXGlue Recompiled Project
- C. Synchronization, Threads & Kernel
- .AddKeybindRow
- fable2_heap_scan.h
- Program
- fable2_frame_capture.h
- B. Memory Management (heap)
- fable2_list_dump.h
- A. Story & Gameplay
- gen_def.py
- fable2_font_probe.h
- Draft issue for KhronosGroup/MoltenVK (not filed)
- Curated export table
- Related repositories, forks and upstream work relevant to the Fable 2 Recomp macOS port
- UITextItem_Dispatch
- trim_exports.py
- gaddr
- modifyMoney.lua
- tools/mac: macOS measurement tools
- Type
- clean_pe.py build orchestrator
- HotFuncYieldSlider
- modifyMoralityPurity.lua
- GameVersion
- rexglue_vulkan_plugin wrapper project
- Dictionary
- fable2_hook_disable_motion_blur mid-asm hook
- test_keyboard_gamepad_map.cpp
- PRs for himdo/rexglue-sdk
- fable_2 executable target
- Hooking recompiled functions (weak wrapper and strong override)
- UIFont_RenderGlyph
- fable_2_recomp_patches custom target
- REXGLUE_SDK_ROOT and REXGLUE_SDK_SOURCE
- vulkan-1.dll loader staging
- UIText_RenderCurrent
- UIText_RenderWithFont
- Launcher Advanced Options page
- Self-contained single-file publish
- Remote control server
- build.sh script
- keyboard_gamepad.h
- prof3d.sh
- Fable 2 (ReXGlue) 30 fps cap — investigation log
- stage_content.sh
- F. String & Math Helpers
- PageWriteGuard
- cstdlib
- Fable 2 (ReXGlue) — Function Names & Reference
- gaddr
- scene.sh
- build_runtime_sdk.sh
- Mapping
- memory.md — Port de Fable 2 Recomp a macOS (Apple Silicon)
- Probe
- Fable 2 Recomp on macOS: what the 2026-10-13 measurements say
- Yield_82CBD098
- Fix: D3D12 / Vulkan source builds crashed at the main menu
- CatalogueTests
- GraphicsOptions.cs
- .ReadDirectory
- gaddr
- menu_arrows.sh
- Action
- prof3d_hold.sh
- vulkan_smoke.cpp
- test_launcher_core.py
- gaddr
- phase.sh
- InputSnapshot
- gaddr
- 1. How the Vulkan backend (fbo path) creates and uses MSAA render targets
- gpucapture.sh
- .PickDevice
- mac/build.sh

## God Nodes (most connected - your core abstractions)
1. `J. Unnamed Body Functions` - 208 edges
2. `I. Trampolines & Getters` - 99 edges
3. `VkFns` - 83 edges
4. `H. Switch / Jump-Table Dispatchers` - 75 edges
5. `MainWindow` - 67 edges
6. `VulkanApp` - 55 edges
7. `ControlServer` - 54 edges
8. `Window` - 53 edges
9. `G. Virtual-Dispatch Thunks (vtable)` - 51 edges
10. `Value` - 33 edges

## Surprising Connections (you probably didn't know these)
- `Otros trabajos de esta sesión` --references--> `Fable2ConfigFile`  [INFERRED]
  memory.md → launcher/Fable2.Launcher/Fable2ConfigFile.cs
- `4. The t3 hang at the title screen (run_t3, log 002, sample_t3)` --references--> `Yield_82CBD098()`  [INFERRED]
  docs/analysis/measured-data.md → src/diagnostics/fps_probe.h
- `4. Estimación y recomendación` --references--> `Key()`  [INFERRED]
  docs/macos-launcher-study.md → src/core/dir_manifest_heal.h
- `Fable 2 (ReXGlue) — Function Names & Reference` --references--> `name()`  [INFERRED]
  FUNCTION_NAMES.md → src/diagnostics/fable2_hotfuncs.h
- `Trampas conocidas` --references--> `host_of()`  [INFERRED]
  memory.md → src/diagnostics/fable2_ui_input_probe.h

## Import Cycles
- None detected.

## Hyperedges (group relationships)
- **Guild chest click flow** — tools_chest_debug_sub_82228c70, tools_chest_debug_guildchest_processitems_822de008, tools_chest_debug_guildchest_processitem_82228830, tools_chest_siblings_sub_8256e4f8, tools_chest_debug_guildchest_getwebsiteitem_8256e368, tools_chest_debug_guildchest_getcecontent_824b3528 [EXTRACTED 1.00]
- **Mod menu selection mirror and activation** — plans_main_menu_mod_item_pressbitdispatch, plans_main_menu_mod_item_mirror_index, plans_main_menu_mod_item_modmenu_module [EXTRACTED 1.00]
- **Remote input injection pipeline** — plans_ai_remote_input_control_remotecontrolserver, plans_ai_remote_input_control_remoteinputstate, plans_ai_remote_input_control_remotegamepaddriver [EXTRACTED 1.00]
- **Hero/dog readback gate path in SDK command processor** — plans_hero_dog_texture_readback_should_force, plans_hero_dog_texture_readback_issuecopy_d3d12, plans_hero_dog_texture_readback_issuecopy_vulkan, plans_hero_dog_texture_readback_draw_indx_2_gate [EXTRACTED 1.00]
- **X360Disc reader stack** — tools_x360extract_lib_readme_x360disc, tools_x360extract_lib_readme_extraction_options, tools_x360extract_lib_readme_gdfxfilesystem, tools_x360extract_lib_readme_isoimage, tools_x360extract_lib_readme_stfscontainer [EXTRACTED 1.00]
- **CMake build-time generated and staged artifacts** — cmakelists_fable2_target, cmakelists_lua_staging, cmakelists_recomp_patches, cmakelists_vulkan_loader [INFERRED 0.75]
- **Guest function hooking and instrumentation probes** — text_rendering_notes_hook_pattern, text_rendering_notes_ui_render_probe, text_rendering_notes_deadbeef_canary, readme_func_trace [INFERRED 0.75]
- **UI text per-frame render chain** — text_rendering_notes_uitext_frame_render, text_rendering_notes_uitext_frame_render_iter, text_rendering_notes_uitext_item_dispatch, text_rendering_notes_uitextprompt_render, text_rendering_notes_uitextprompt_renderelement, text_rendering_notes_sub_82c12f18 [INFERRED 0.85]

## Communities (153 total, 28 thin omitted)

### Community 0 - "xex_verify.h"
Cohesion: 0.08
Nodes (32): Check(), DefaultLanguage(), HasCompatibleContent(), IsAcceptedHash(), IsEnabledVersion(), Marker, hash, mtime (+24 more)

### Community 1 - "fable2_ui_input_probe.h"
Cohesion: 0.08
Nodes (52): add_runtime_addr(), all_regs(), anchor_is_proc(), be32(), decode_u16be(), delay_seconds(), dump_bytes(), dump_cap() (+44 more)

### Community 2 - "fable2_state_probe.h"
Cohesion: 0.05
Nodes (48): Cambios hechos en la rama `macos-port`, aread(), arena(), be32(), boot_ms(), CurrentFrontEndValue(), CurrentState(), CurrentStateName() (+40 more)

### Community 3 - "VkFns"
Cohesion: 0.04
Nodes (14): VkFns, destroy_command_pool, destroy_device, destroy_fence, destroy_framebuffer, destroy_image_view, destroy_instance, destroy_render_pass (+6 more)

### Community 4 - "GamepadDriver"
Cohesion: 0.10
Nodes (7): GamepadDriver, enabled_, have_prev_, kDeviceId, packet_number_, prev_, state_

### Community 5 - "Fable2ConfigValues"
Cohesion: 0.07
Nodes (27): Fable2ConfigValues, CameraDistance, CameraEyeOff, CameraRotCurOff, CameraRotTgtOff, DirectMouseLook, DisableMotionBlur, DogFurDepthBias (+19 more)

### Community 6 - "fable2_modmenu.h"
Cohesion: 0.09
Nodes (35): Activate(), arm_scanner(), enabled(), find_downloadable(), find_needle(), FrontMenu_PressBitDispatch(), host_addr(), in_main_menu() (+27 more)

### Community 7 - "VulkanApp"
Cohesion: 0.05
Nodes (26): VulkanApp, command_buffers, command_pool, device, extent, fns, format, frame (+18 more)

### Community 8 - "fable2_av_probe.h"
Cohesion: 0.09
Nodes (24): handler(), in_guest_mem(), is_guest_ctx(), log_line(), ProbeState, counts, diag_logged, keys (+16 more)

### Community 9 - "fable2_text_append.h"
Cohesion: 0.11
Nodes (29): adv(), append_segment(), collect_subitems(), dump_char_cands(), dump_words(), element_is_safe(), find_last_element(), guest_alloc() (+21 more)

### Community 10 - "fable_2_pch"
Cohesion: 0.08
Nodes (31): gaddr(), gload32(), gload8(), gstore32(), gstore8(), gaddr(), gload32(), gload64() (+23 more)

### Community 11 - "remote_control_server.h"
Cohesion: 0.07
Nodes (29): ClampForSlot(), ClearSlotInSnapshot(), IsTriggerSlot(), Slot, kBtnA, kBtnB, kBtnBack, kBtnDown (+21 more)

### Community 12 - "Value"
Cohesion: 0.20
Nodes (12): IsStickSlot(), JEsc(), Parse(), SlotFromName(), SlotName(), Value, arr, boolean (+4 more)

### Community 13 - "ControlServer"
Cohesion: 0.08
Nodes (20): CloseSock(), Config, host, port, token, ControlServer, cfg_, client_socket_ (+12 more)

### Community 14 - "Fable2ConfigFile"
Cohesion: 0.16
Nodes (4): Fable2ConfigFile, KeybindEntry, Button, Key

### Community 15 - "Window"
Cohesion: 0.08
Nodes (41): AdvancedContent, AdvancedFooter, AdvancedStatusText, AnisotropicCombo, AntiAliasingCombo, ConfigStateText, DirectMouseLookCheck, DisplayModeCombo (+33 more)

### Community 16 - "Hero dog targeted readback plan"
Cohesion: 0.07
Nodes (29): Baked morph mode (flag 0), sub_82A55EC0 morph output format selection, fable2_hook_realtime_texture_morphing at 0x82A7607C, sub_82A76018 morph job creation, sub_82A69728 morph renderer, Realtime texture morphing plan, Realtime morph mode (flag 1), Hero and dog texture address 0x12704000 (+21 more)

### Community 17 - "X360Disc"
Cohesion: 0.08
Nodes (21): DiscExtraction, DefaultXex, Gdfx, IsoPath, Plan, RootEntries, TotalBytes, GdfxEntry (+13 more)

### Community 18 - "KeyboardGamepadDriver"
Cohesion: 0.09
Nodes (11): KeyboardGamepadDriver, bindings_, cached_text_, console_open_, cursor_hidden_, kDeviceId, mouse_centered_, packet_number_ (+3 more)

### Community 19 - "RoutedEventArgs"
Cohesion: 0.13
Nodes (10): AdvancedOptionsButton, CancelButton, ExtractAnywaysButton, ExtractButton, HotFuncYieldBox, LaunchButton, MouseSensitivityBox, StopButton (+2 more)

### Community 20 - "Idx"
Cohesion: 0.07
Nodes (27): Idx, kCount, kSub_82A6EF40, kSub_82A8D2D0, kSub_82C09018, kSub_82C12CF8, kSub_82C12D00, kSub_82C12D90 (+19 more)

### Community 21 - "ExtractionProgress"
Cohesion: 0.12
Nodes (14): ExtractionCancelledException, ExtractionProgress, CompletedBytes, CurrentFile, CurrentFileSize, CurrentFileWritten, Percent, Phase (+6 more)

### Community 22 - "sys"
Cohesion: 0.10
Nodes (8): main(), load(), T(), T(), T(), T(), load(), val()

### Community 23 - "fable2_patches.h"
Cohesion: 0.14
Nodes (11): Memory, Op, address, value, width, Patch, author, desc (+3 more)

### Community 24 - "fable2_deadbeef.h"
Cohesion: 0.12
Nodes (35): append(), gread(), gwrite(), host_addr(), host_writable(), in_image(), is_heap_ptr(), is_text() (+27 more)

### Community 25 - "cstdint"
Cohesion: 0.15
Nodes (7): 1. Mid-asm hooks (preferred) — SDK-native, declarative, BatchedYield(), SkippedYieldFence(), GuestByte(), GuestPtr(), name(), start_writer()

### Community 26 - "fable2_patches.cpp"
Cohesion: 0.16
Nodes (9): ApplyAll(), ToBeHex(), Width, kBe16, kBe32, kBe64, kBe8, WidthBytes() (+1 more)

### Community 27 - "fable2_func_trace.h"
Cohesion: 0.07
Nodes (22): commit_run(), ensure_sweeper(), Fable2FuncTraceFlush(), Fable2FuncTraceSetEnabled(), file(), final_summary_guard, flush(), flush_buffer() (+14 more)

### Community 28 - "fable2_ui_render_probe.h"
Cohesion: 0.05
Nodes (45): 10. Bank TOC decoding (update — names are NOT opaque hashes), 11. White-square override (implemented, code-only, no art changed), 12. Open questions / suggested next steps, 1. Short answer, 2. The asset and its container, 3. Stage 1 — VFS bank registration (boot), 4. Stage 2 — GameFace presentation load (main menu), 5. Stage 3 — runtime memory (proof of initialization) (+37 more)

### Community 29 - "MainWindow.xaml.cs"
Cohesion: 0.09
Nodes (7): Fable2Launcher.Constants, Fable2Launcher, X360Extract, Application, App, GameLaunchPlan, GameLaunchPlanner

### Community 30 - "J. Unnamed Body Functions"
Cohesion: 0.01
Nodes (208): `AccumulateGlobalCallback_82BC30D0`, `AllocateNode28_82A12B90`, `Array_InsertAt_82370A98`, `Array_InsertOne_8236FDD8`, `Array_Push12_82C66E00`, `Array_Push28_82C644D0`, `Array_PushBack_82C21E08`, `Array_PushElement_823758C0` (+200 more)

### Community 31 - "I. Trampolines & Getters"
Cohesion: 0.02
Nodes (99): `CheckPrefixedWord_ReturnZeroOrComplement_832B3D78`, `ConstTrue_Predicate_82C43198`, `GetCurrentTimeMs`, `GetElapsedMsSinceStart`, `GetPtr_Field32_824C23D0`, I. Trampolines & Getters, `IndirectCall_83095890`, `IndirectCall_8310FC68` (+91 more)

### Community 32 - "subprocess"
Cohesion: 0.40
Nodes (5): fail(), git(), libmspack_mode(), main(), patch_state()

### Community 33 - "F5.lua"
Cohesion: 0.13
Nodes (15): Memory::AccessViolationCallback, Guest read of 0x00000000 access violation, F5 guest null access violation plan, poll_mainloop MainRenderLoop hook, run_external pre-call validation of this and head, run_external, CScriptManager::RunScript (0x825ADB40), build_page() (+7 more)

### Community 34 - "fps_probe.h"
Cohesion: 0.27
Nodes (12): DelayMilliseconds_82CC2028(), MainRenderLoop_82B9CD68(), note(), note_exit(), ProcessAndProcessAndProcess1087_82242628(), ProcessAndProcessAndProcess1260_82BA32C8(), sub_82B9B8D8(), sub_82B9F598() (+4 more)

### Community 35 - "CallActivePlayerMethod_821A11E8.cpp"
Cohesion: 0.42
Nodes (8): gaddr(), gload32(), gload64(), gload8(), gstore32(), gstore64(), gstore8(), vcall()

### Community 36 - "MainWindow"
Cohesion: 0.11
Nodes (3): 1. Inventario del launcher de Windows y equivalente en macOS, LauncherState, MainWindow

### Community 37 - "H. Switch / Jump-Table Dispatchers"
Cohesion: 0.03
Nodes (75): H. Switch / Jump-Table Dispatchers, `StateDispatch_82BCA7D8`, `StateDispatch_82BCBB40`, `SwitchDispatch_8217F250`, `SwitchDispatch_8222B3C8`, `SwitchDispatch_822D7C50`, `SwitchDispatch_822D7CB0`, `SwitchDispatch_822D7D58` (+67 more)

### Community 38 - "fable2_glyph_probe.h"
Cohesion: 0.31
Nodes (15): dump_block(), dump_glyphrun(), dump_item(), dump_str(), dump_words(), host_addr(), load_be(), log_line() (+7 more)

### Community 39 - "struct"
Cohesion: 0.23
Nodes (13): add_version_resource(), _align(), _binary_value(), _build_rsrc(), build_vs_version_info(), e_lfanew(), main(), _pad() (+5 more)

### Community 40 - ".Classify"
Cohesion: 0.29
Nodes (5): GameVersion, GameVersions, 2. Lo específico de macOS, GameCompatibility, GameCompatibilityInspector

### Community 41 - "IsoImage"
Cohesion: 0.16
Nodes (11): IsoEntry, IsDirectory, IsFile, IsoEntryKind, Directory, File, Parent, VolumeTag (+3 more)

### Community 42 - "Parser"
Cohesion: 0.35
Nodes (4): Parser, end_, err_, p_

### Community 43 - "chest_siblings.txt 8-sibling item-op dispatch script"
Cohesion: 0.14
Nodes (16): chest_click.txt ready-state breakpoint script, GuildChest_GetCEContent (824B3528), GuildChest_GetWebsiteItem (8256E368), GuildChest_ProcessItem (82228830), GuildChest_ProcessItems (822DE008), chest_debug.txt full WinDbg breakpoint script, Click handler sub_82228C70, GuildChest_GetWebsiteItem (8256E368) sibling entry (+8 more)

### Community 44 - ".Init"
Cohesion: 0.17
Nodes (7): create_device, create_swapchain, create_win32_surface, get_device_queue, get_surface_capabilities, get_surface_formats, get_swapchain_images

### Community 46 - "fable2_modmenu.h mod menu module"
Cohesion: 0.13
Nodes (15): Background front-end string scanner thread, UITextContainer_ProcessChildren, Downloadable Content row repurposed as MOD MENU, FrontMenu_InputEvent (0x82BE3F30), Selection mirror index 0..5, fable2_modmenu.h mod menu module, Main menu mod item plan, FrontMenu_PollEventQueue (0x82185C90) (+7 more)

### Community 47 - "Interval"
Cohesion: 0.16
Nodes (10): Interval, end, open, slot, start, value, ResolveTimeline(), Timeline (+2 more)

### Community 48 - "Parte A — T3: teselación continua emulada en el vertex shader"
Cohesion: 0.13
Nodes (14): A.0 Cómo funciona hoy (lo que hay que reproducir), A.1 Tipo nuevo y `Modification`, A.2 Selección e índices (`primitive_processor.cpp`), A.3 Traductor (`spirv_translator.cpp`), A.4 Pipeline y backend, A.5 Riesgos y verificación, A.6 Líneas y orden, B.1 Opción (a'): esperar la fence del slot si ya está enviado; saltar solo si es de la submission abierta (+6 more)

### Community 49 - "clean_pe.py"
Cohesion: 0.14
Nodes (16): clean_dir(), export_names(), import_names_from(), main(), r2o(), read_sections(), sha256(), trim_export_table() (+8 more)

### Community 50 - "argparse"
Cohesion: 0.17
Nodes (10): build_state(), conn(), exchange(), main(), run(), generate(), main(), git() (+2 more)

### Community 51 - "Values"
Cohesion: 0.07
Nodes (28): Values, camera_distance, camera_eye_off, camera_rot_cur_off, camera_rot_tgt_off, config_version, direct_mouse_look, disable_motion_blur (+20 more)

### Community 52 - "X360Disc facade"
Cohesion: 0.14
Nodes (15): ExtractionOptions, GdfxFilesystem, IsoImage, NuGet packaging of X360Extract library, StfsContainer, X360Disc facade, Fable II launcher (library consumer), GDFX directory tree walk (+7 more)

### Community 54 - "cstdio"
Cohesion: 0.18
Nodes (4): DeadbeefDialog, enabled(), register_overlay(), scale()

### Community 55 - "fable2_stall_dump.h"
Cohesion: 0.23
Nodes (10): dump_threads(), fmt_ip(), loop(), ModuleRange, base, end, name, safe_read() (+2 more)

### Community 56 - "fable2_launcher.py"
Cohesion: 0.06
Nodes (13): TestGameCatalog, TestPresets, TestTomlConfigManager, apply_preset(), cli_main(), GameCatalog, GdfxExtractor, recurse() (+5 more)

### Community 57 - "LauncherViewModel"
Cohesion: 0.08
Nodes (21): AppKit, BottomBarView, .body, ContentView, .body, DisplaySettingsCard, .body, ExtractionProgress (+13 more)

### Community 58 - "context"
Cohesion: 0.11
Nodes (7): fable2_hook_address_scan_skip(), FirstConflictEnd(), Memory, RoundUp(), SetMemory(), Read(), TypeName()

### Community 59 - "ProcessGameFrame_82276C30 hand-tuned override"
Cohesion: 0.18
Nodes (10): decrement_global_counter CAS helper, compute_loop_timing, Goto elimination into if/else and do-while, guest_fma helper (target fma), tools/make_hotfunc_overrides.py, ProcessGameFrame hand-tune plan, ProcessGameFrame_82276C30 hand-tuned override, Region helpers (probe_and_setup and siblings) (+2 more)

### Community 60 - "cstring"
Cohesion: 0.23
Nodes (6): logf(), logline(), LuaBind_RunScript_82806168(), poll_f5(), poll_mainloop(), run_external()

### Community 61 - "fable_2_app.h"
Cohesion: 0.11
Nodes (6): DetectEol(), EnsureComplete(), Key(), GetWindowPresenter(), WindowPresenterAccessor, Apply()

### Community 62 - "mouse_look.h"
Cohesion: 0.08
Nodes (42): Current patches (both default to **disabled**), fable2_hook_ce_g1(), fable2_hook_ce_g1b(), fable2_hook_ce_grantavail(), fable2_hook_direct_mouse_look(), fable2_hook_disable_motion_blur(), fable2_hook_high_hf_tick_rate_skip_store(), fable2_hook_high_tick_rate_skip_store() (+34 more)

### Community 63 - "Tareas"
Cohesion: 0.10
Nodes (20): Hecho (resumen; detalle en `memory.md` y en el log de git), Línea base medida (escena 3D, 1 frame ≈ 142 ms), Para la próxima sesión (anotado 2026-10-13, noche), Reglas para todas las tareas, T0. Herramientas de medida en el repo — hecho, T10. MSAA en MoltenVK: diagnóstico cerrado (2026-10-16) y modo de 1 muestra en el host, T11. Point sprites (nieve): el freno que queda para 30 FPS (2026-10-17), T1. Subidas de shared memory fuera del render pass — hecha (cvar on por defecto en macOS) (+12 more)

### Community 64 - "G. Virtual-Dispatch Thunks (vtable)"
Cohesion: 0.04
Nodes (51): G. Virtual-Dispatch Thunks (vtable), `VtableSlot1_82BFA4A8`, `VtableSlot26_82F04420`, `VtableSlot29_824F0600`, `VtableSlot2_82903F80`, `VtableSlot5_82903F70`, `VtableSlot6_82C1DC60`, `VtableSlot7_82C1DC50` (+43 more)

### Community 65 - "fable2_ui_text_dump.h"
Cohesion: 0.27
Nodes (10): dump(), env_dbl(), env_long(), now_s(), page_readable(), plausible(), safe_read(), safe_read32() (+2 more)

### Community 66 - "gaddr"
Cohesion: 0.53
Nodes (6): gaddr(), gload32(), gload64(), gstore32(), gstore64(), gstore8()

### Community 67 - "gdfx_extract.py"
Cohesion: 0.50
Nodes (3): main(), read_dir(), walk()

### Community 68 - "X360Extract.Core.csproj"
Cohesion: 0.17
Nodes (8): net8.0-windows, Microsoft.NET.Sdk, net8.0, Microsoft.NET.Sdk, net8.0, Microsoft.NET.Sdk, net8.0, Microsoft.NET.Sdk

### Community 70 - "RemoteControlServer"
Cohesion: 0.23
Nodes (9): tools/fable2_control.py client, Game state classifier (game_state command), JSON-lines TCP protocol, KeyboardGamepadDriver, AI Remote Input Control Plan, RemoteControlServer, RemoteGamepadDriver, RemoteInputState (+1 more)

### Community 71 - "ProcessGameFrame_82276C30.cpp"
Cohesion: 0.33
Nodes (10): check_loop_backedge(), compute_frame_timing(), compute_loop_timing(), decrement_global_counter(), frame_gate(), guest_fma(), probe_and_setup(), process_frame_work() (+2 more)

### Community 72 - ".CreateRenderPassAndCommands"
Cohesion: 0.17
Nodes (11): allocate_command_buffers, begin_command_buffer, cmd_begin_render_pass, cmd_end_render_pass, create_command_pool, create_fence, create_framebuffer, create_image_view (+3 more)

### Community 73 - "Fable 2 ReXGlue Recompiled Project"
Cohesion: 0.12
Nodes (15): Application icon (asset provenance), FABLE2_CODEGEN_TOOL, FABLE2_BUILD_PROFILE selection, Shared version catalogue (game_versions.json), German GOTY support, Behavior, Build, Validation and remaining limits (+7 more)

### Community 74 - "C. Synchronization, Threads & Kernel"
Cohesion: 0.07
Nodes (29): `BugCheck_82CA9660`, `BugCheck_82CA9710`, `BugCheck_82CB57CC`, `BugCheck_82CB57D4`, `BugCheck_82CB57E0`, C. Synchronization, Threads & Kernel, `CriticalSection_EnterOrTry_82200688`, `CriticalSection_ProcessEntryArray_832B3700` (+21 more)

### Community 75 - ".AddKeybindRow"
Cohesion: 0.14
Nodes (6): 3. Comparativa de opciones, 5. Decisiones que necesita el usuario, Cuánto del C# es portable (cuenta en ficheros y líneas), Launcher para macOS: estudio (T7), Tabla, KeyCaptureField

### Community 76 - "fable2_heap_scan.h"
Cohesion: 0.31
Nodes (9): env_int(), maybe_request(), needle_search(), now_s(), ptr_backref_search(), scan_all(), seh_dump_runs(), start_scanner_once() (+1 more)

### Community 77 - "Program"
Cohesion: 0.47
Nodes (3): OptionException, Options, Program

### Community 78 - "fable2_frame_capture.h"
Cohesion: 0.17
Nodes (14): Adler32(), CaptureGuestOutputToPng(), PngChunk(), PutBE16(), PutBE32(), Result, avg_luma, bytes (+6 more)

### Community 79 - "B. Memory Management (heap)"
Cohesion: 0.09
Nodes (23): `Allocate_Init_821A9258`, `Allocate_OrDbgBreak_8221F388`, `Allocate_SizeBucketed_83231D20`, `Allocate_SizeBucketed_Thunk_8221F3F0`, B. Memory Management (heap), `CopyAssign_RefCounted_821F0108`, `Free_SizeBucketed_83231BE8`, `Free_SizeBucketed_Thunk_8221BE68` (+15 more)

### Community 80 - "fable2_list_dump.h"
Cohesion: 0.47
Nodes (7): td_dump_block(), td_follow(), td_now(), td_rd(), textobj_dump(), textobj_hook(), UIText_FrameRender()

### Community 81 - "A. Story & Gameplay"
Cohesion: 0.10
Nodes (20): A. Story & Gameplay, `GetNewGameLoadingGlobal`, `LoadingScreen_VectorOffset`, `LoadingScreen_Virtual28`, `LoadingScreen_Virtual36`, `LoadingScreen_Virtual39`, `LoadingScreen_Virtual42`, `LoadingScreen_Virtual43` (+12 more)

### Community 82 - "gen_def.py"
Cohesion: 0.47
Nodes (3): consumer_imports(), dll_exports(), main()

### Community 83 - "fable2_font_probe.h"
Cohesion: 0.36
Nodes (10): enabled(), every(), find_prompt(), load_be(), log_line(), maybe_scan(), page_rw(), scan() (+2 more)

### Community 84 - "Draft issue for KhronosGroup/MoltenVK (not filed)"
Cohesion: 0.22
Nodes (8): Draft issue for KhronosGroup/MoltenVK (not filed), History, Observed, Proposed fix, Reproduction (generic), Summary, Which object, Workaround

### Community 85 - "Curated export table"
Cohesion: 0.31
Nodes (7): BitDefender Ulise generic heuristic detection, Authenticode code signing, Curated export table, Host exe to rexruntime.dll ABI contract, AV-clean builds plan, VS_VERSION_INFO resource, VirusTotal gate (Phase 4 ops)

### Community 86 - "Related repositories, forks and upstream work relevant to the Fable 2 Recomp macOS port"
Cohesion: 0.15
Nodes (12): 0. Lineage of the Fable 2 projects, 1.1 Apple / MoltenVK / Metal forks, 1.2 GPU / performance forks (not Apple-specific), 1. Forks of rexglue/rexglue-sdk and himdo/rexglue-sdk with their own commits, 2.1 andrew17182/Fable-2-Recomp: Fable 2 on a native Metal plugin (XeniOS backend), 2.2 XeniOS (the Metal backend itself), 2.3 Other ReXGlue titles on macOS, 2. Other ReXGlue games on macOS or with GPU performance work (+4 more)

### Community 87 - "UITextItem_Dispatch"
Cohesion: 0.22
Nodes (9): DEADBEEF canary (UI text append), Localized Press A to start prompt strings, sub_82C12F18 (draw-object vtable slot 8), Font / UI-text rendering pipeline, UIText_FrameRender, UIText_FrameRenderIter, UITextItem_Dispatch, UITextPrompt_Render (+1 more)

### Community 88 - "trim_exports.py"
Cohesion: 0.39
Nodes (7): e_lfanew(), main(), read_def_names(), read_sections(), rva_to_offset(), trim(), name_at()

### Community 89 - "gaddr"
Cohesion: 0.53
Nodes (5): gaddr(), gload32(), gload64(), gstore32(), gstore64()

### Community 90 - "modifyMoney.lua"
Cohesion: 0.43
Nodes (6): apply_amount(), build_page(), get_hero(), open_money_menu(), run(), settle_box()

### Community 91 - "tools/mac: macOS measurement tools"
Cohesion: 0.40
Nodes (4): Analizar una traza de Metal, Protocolo de medida, Scripts, tools/mac: macOS measurement tools

### Community 92 - "Type"
Cohesion: 0.29
Nodes (7): Type, Array, Bool, Null, Number, Object, String

### Community 93 - "clean_pe.py build orchestrator"
Cohesion: 0.38
Nodes (5): BitDefender Ulise generic AV flag, clean_pe.py build orchestrator, rexruntime.dll export table trimming (~10140 to ~3919), normalize_pe.py core normalizer, Volatile PE fields pinned by normalizer

### Community 94 - "HotFuncYieldSlider"
Cohesion: 0.40
Nodes (3): HotFuncYieldSlider, MouseSensitivitySlider, Slider

### Community 95 - "modifyMoralityPurity.lua"
Cohesion: 0.47
Nodes (3): open_menu(), run(), settle_box()

### Community 96 - "GameVersion"
Cohesion: 0.16
Nodes (12): Find(), GameVersion, code_group, compatible, hash, id, language, name (+4 more)

### Community 97 - "rexglue_vulkan_plugin wrapper project"
Cohesion: 0.33
Nodes (3): Dual D3D12 and Vulkan rexruntime superset, REXGLUE_SDK_SOURCE variable, rexglue_vulkan_plugin wrapper project

### Community 98 - "Dictionary"
Cohesion: 0.22
Nodes (3): 4. Estimación y recomendación, GraphicsSettings, LauncherConfigFile

### Community 99 - "fable2_hook_disable_motion_blur mid-asm hook"
Cohesion: 0.60
Nodes (5): sub_822A47C0 camera per-frame update, [patches] disable_motion_blur toggle, Disable motion blur plan, Renderer blur request (camera +0xD4), fable2_hook_disable_motion_blur mid-asm hook

### Community 100 - "test_keyboard_gamepad_map.cpp"
Cohesion: 0.36
Nodes (3): CheckBinding(), Find(), RegisterFlag()

### Community 101 - "PRs for himdo/rexglue-sdk"
Cohesion: 0.50
Nodes (3): Notes on remaining candidates, Open Pull Requests, PRs for himdo/rexglue-sdk

### Community 102 - "fable_2 executable target"
Cohesion: 0.50
Nodes (4): fable_2 executable target, fable_2_lua_staging custom target, FABLE2_PROFILER_FRIENDLY option, F5 external Lua script

### Community 103 - "Hooking recompiled functions (weak wrapper and strong override)"
Cohesion: 0.50
Nodes (3): Guest function-call tracing (fable2_func_trace.log), PPCContext (emulated register file), fable2_ui_render_probe.h (UI render probe)

### Community 104 - "UIFont_RenderGlyph"
Cohesion: 0.67
Nodes (3): UIFont_EmitGlyphQuad, UIFont_RenderGlyph, UIText_RenderElement (per-glyph draw)

### Community 117 - "keyboard_gamepad.h"
Cohesion: 0.11
Nodes (12): ApplyRelativeMouse(), ClampStick(), KeyDown(), button, MouseVk(), OnKeyDown(), OnKeyUp(), OnMouseDown() (+4 more)

### Community 119 - "Fable 2 (ReXGlue) 30 fps cap — investigation log"
Cohesion: 0.12
Nodes (15): Begin-frame deadline math (`BeginFrame_82B9BA58`, recomp.289:19537+), Cleanup done, Decisive experiment (this session), Fable 2 (ReXGlue) 30 fps cap — investigation log, Files, If revisiting, Key guest functions (recompiled, `generated/default/`), Limiter anatomy (`FrameLimiterWait_82242628`) (+7 more)

### Community 121 - "F. String & Math Helpers"
Cohesion: 0.12
Nodes (16): `Ctype_IsUpper_82CA6AD0`, `Ctype_Pred_Bit2_82CA6B10`, F. String & Math Helpers, `FNV1Hash_821F3C28`, `FNV1Hash_CaseInsensitive_82448030`, `Math_FloatIndexStore_824D56C8`, `MemCpy_Aligned_82CA30E8`, `MemCpy_SdkRuntime_82CA2C60` (+8 more)

### Community 122 - "PageWriteGuard"
Cohesion: 0.17
Nodes (9): BuildPatches(), Flip, page, size, PageWriteGuard, access_, flipped_, heap_ (+1 more)

### Community 123 - "cstdlib"
Cohesion: 0.21
Nodes (6): Fable2FuncTraceSetFilter(), delay_seconds(), duration_seconds(), enabled(), MainRenderLoop_82B9CD68(), run_window()

### Community 124 - "Fable 2 (ReXGlue) — Function Names & Reference"
Cohesion: 0.17
Nodes (11): D. Exceptions & Fatal Errors, E. Filesystem / Volume, `Exception_82CC02FC`, `Exception_82CC031C`, `Exception_82CC032C`, Fable 2 (ReXGlue) — Function Names & Reference, `FatalError_82CBB98C`, `FatalError_82CBBB24` (+3 more)

### Community 125 - "gaddr"
Cohesion: 0.53
Nodes (5): gaddr(), gload32(), gload64(), gstore32(), gstore64()

### Community 129 - "Mapping"
Cohesion: 0.22
Nodes (10): FillGuestTarget(), Mapping, axis, axis_sign, trigger, vk, ParseKey(), ParseMap() (+2 more)

### Community 130 - "memory.md — Port de Fable 2 Recomp a macOS (Apple Silicon)"
Cohesion: 0.04
Nodes (30): 2. Post-codegen text patches (fallback), Current recomp-level patches, Follow-ups, FPS meter, Guest-image patch system (Xenia patch format), How it works, Recomp-level patches (making code patches work), Validation (2026-09-15) (+22 more)

### Community 131 - "Probe"
Cohesion: 0.20
Nodes (9): Probe, calls, in_flight_us, last_us, logged, max_dur_us, max_us, min_us (+1 more)

### Community 132 - "Fable 2 Recomp on macOS: what the 2026-10-13 measurements say"
Cohesion: 0.25
Nodes (7): 1. Per-run MoltenVK numbers, steady 3D window, 2. Where the frame goes (full, 67.5 ms), 3. What changed base -> t3only -> full, vs the design expectations, 4. The t3 hang at the title screen (run_t3, log 002, sample_t3), 5. Ranked remaining bottlenecks (full build, 67.5 ms/frame) and what is measured vs inferred, Fable 2 Recomp on macOS: what the 2026-10-13 measurements say, Method and caveats

### Community 133 - "Yield_82CBD098"
Cohesion: 0.29
Nodes (7): What was ruled out (earlier sessions), Current overrides, Hand-tuned overrides, Hot-function overrides (strong-symbol copies of recompiled guest code), Mechanism, Rules for new copies, Yield_82CBD098()

### Community 134 - "Fix: D3D12 / Vulkan source builds crashed at the main menu"
Cohesion: 0.33
Nodes (5): Fix, Fix: D3D12 / Vulkan source builds crashed at the main menu, Notes, Root cause, Verification

### Community 146 - "gaddr"
Cohesion: 0.53
Nodes (5): gaddr(), gload32(), gload64(), gstore32(), gstore64()

### Community 147 - "menu_arrows.sh"
Cohesion: 0.70
Nodes (4): at(), cap(), key(), menu_arrows.sh script

### Community 148 - "Action"
Cohesion: 0.17
Nodes (7): DiscProgress, DiscProgressPhase, EnteringDirectory, ExpandingStfs, FileWritten, ScanningHeader, WritingFile

### Community 152 - "vulkan_smoke.cpp"
Cohesion: 0.14
Nodes (8): LoadVulkan(), PauseExit(), acquire_next_image, queue_present, queue_submit, reset_fences, wait_for_fences, WinMain()

### Community 153 - "test_launcher_core.py"
Cohesion: 0.10
Nodes (5): ConfigParityTests, toml_keys(), diff(), luma(), main()

### Community 155 - "gaddr"
Cohesion: 0.53
Nodes (5): gaddr(), gload32(), gload64(), gstore32(), gstore64()

### Community 159 - "InputSnapshot"
Cohesion: 0.11
Nodes (12): InputSnapshot, buttons, left_trigger, right_trigger, stk_lx, stk_ly, stk_rx, stk_ry (+4 more)

### Community 160 - "gaddr"
Cohesion: 0.52
Nodes (7): gaddr(), gload32(), gload64(), gload8(), gstore32(), gstore64(), gstore8()

### Community 161 - "1. How the Vulkan backend (fbo path) creates and uses MSAA render targets"
Cohesion: 0.09
Nodes (18): 1.1 Path selection and capability probing, 1.2 Host image creation (`VulkanRenderTarget` creation, RTC:1866-1900), 1.3 Render pass / dynamic rendering (no resolve attachments anywhere), 1.4 Graphics pipelines (pipeline_cache.cpp:3279-3309), 1.5 EDRAM ownership transfers between host render targets (`PerformTransfersAndResolveClears`, RTC:4549), 1.6 Dumps and resolves, 1.7 What the SPIR-V translator emits that depends on MSAA (`spirv_translator.cpp`, `_rb.cpp`), 1. How the Vulkan backend (fbo path) creates and uses MSAA render targets (+10 more)

### Community 166 - ".PickDevice"
Cohesion: 0.40
Nodes (4): enumerate_physical_devices, get_properties, get_queue_family_properties, get_surface_support

## Ambiguous Edges - Review These
- `Dog 512x512 fmt6 5-mip chain` → `Shimmer hypothesis: dynamic 256 mip0 overlaps 512 mip0`  [AMBIGUOUS]
  plans/hero-dog-shifty-texture-mipmap.md · relation: references
- `Dynamic 256x256 fmt3 sampled texture` → `Shimmer hypothesis: dynamic 256 mip0 overlaps 512 mip0`  [AMBIGUOUS]
  plans/hero-dog-shifty-texture-mipmap.md · relation: references

## Knowledge Gaps
- **461 isolated node(s):** `id`, `hash`, `name`, `compatible`, `reason` (+456 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 1492 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **28 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Fable 2 (ReXGlue) — Function Names & Reference` connect `Fable 2 (ReXGlue) — Function Names & Reference` to `G. Virtual-Dispatch Thunks (vtable)`, `H. Switch / Jump-Table Dispatchers`, `C. Synchronization, Threads & Kernel`, `B. Memory Management (heap)`, `A. Story & Gameplay`, `cstdint`, `F. String & Math Helpers`, `J. Unnamed Body Functions`, `I. Trampolines & Getters`?**
  _High betweenness centrality (0.249) - this node is a cross-community bridge._
- **What connects `id`, `hash`, `name` to the rest of the system?**
  _461 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `xex_verify.h` be split into smaller, more focused modules?**
  _Cohesion score 0.08084163898117387 - nodes in this community are weakly interconnected._
- **Why does `name()` connect `cstdint` to `Fable 2 (ReXGlue) — Function Names & Reference`?**
  _High betweenness centrality (0.231) - this node is a cross-community bridge._
- **Should `fable2_ui_input_probe.h` be split into smaller, more focused modules?**
  _Cohesion score 0.07832080200501253 - nodes in this community are weakly interconnected._

### Low-confidence Hints
_AMBIGUOUS edges — the extractor was unsure. Verify before acting on these._

- **What is the exact relationship between `Dog 512x512 fmt6 5-mip chain` and `Shimmer hypothesis: dynamic 256 mip0 overlaps 512 mip0`?**
  _Edge tagged AMBIGUOUS (relation: references) - confidence is low._
- **What is the exact relationship between `Dynamic 256x256 fmt3 sampled texture` and `Shimmer hypothesis: dynamic 256 mip0 overlaps 512 mip0`?**
  _Edge tagged AMBIGUOUS (relation: references) - confidence is low._