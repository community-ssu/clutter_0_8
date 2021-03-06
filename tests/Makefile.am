if BUILD_TESTS

noinst_PROGRAMS = test-textures test-events test-offscreen test-scale \
                  test-actors test-behave test-text test-entry test-project \
		  test-perspective test-rotate test-depth \
		  test-threads test-timeline test-timeline-dup-frames \
                  test-timeline-interpolate test-timeline-rewind \
                  test-timeline-smoothness \
		  test-threads test-timeline test-score test-script \
		  test-model test-grab test-effects test-fullscreen \
		  test-shader test-unproject test-viewport test-fbo \
		  test-opacity test-multistage \
		  test-cogl-primitives test-cogl-tex-tile \
		  test-cogl-tex-convert test-cogl-tex-foreign \
		  test-cogl-tex-getset test-cogl-offscreen \
		  test-cogl-tex-polygon test-stage-read-pixels \
		  test-random-text test-clip test-paint-wrapper \
		  test-texture-quality test-entry-auto test-layout \
		  test-invariants test-label-cache test-pick

if X11_TESTS
noinst_PROGRAMS += test-pixmap
noinst_PROGRAMS += test-devices
endif

INCLUDES = -I$(top_srcdir)/ -I$(top_srcdir)/clutter -I$(top_builddir)/clutter
LDADD = $(top_builddir)/clutter/libclutter-@CLUTTER_FLAVOUR@-@CLUTTER_MAJORMINOR@.la
AM_CFLAGS = $(CLUTTER_CFLAGS)
AM_LDFLAGS = $(CLUTTER_LIBS)

test_textures_SOURCES    = test-textures.c
test_events_SOURCES      = test-events.c
test_offscreen_SOURCES   = test-offscreen.c
test_scale_SOURCES       = test-scale.c
test_actors_SOURCES      = test-actors.c
test_grab_SOURCES        = test-grab.c
test_behave_SOURCES      = test-behave.c
test_text_SOURCES        = test-text.c
test_entry_SOURCES       = test-entry.c
test_project_SOURCES     = test-project.c
test_unproject_SOURCES   = test-unproject.c
test_perspective_SOURCES = test-perspective.c
test_rotate_SOURCES      = test-rotate.c
test_depth_SOURCES       = test-depth.c
test_threads_SOURCES     = test-threads.c
test_timeline_SOURCES    = test-timeline.c
test_timeline_dup_frames_SOURCES  = test-timeline-dup-frames.c
test_timeline_interpolate_SOURCES = test-timeline-interpolate.c
test_timeline_rewind_SOURCES      = test-timeline-rewind.c
test_timeline_smoothness_SOURCES  = test-timeline-smoothness.c
test_shader_SOURCES               = test-shader.c
test_score_SOURCES                = test-score.c
test_script_SOURCES               = test-script.c
test_model_SOURCES                = test-model.c
test_effects_SOURCES              = test-effects.c
test_fullscreen_SOURCES           = test-fullscreen.c
test_viewport_SOURCES             = test-viewport.c
test_fbo_SOURCES                  = test-fbo.c
test_opacity_SOURCES              = test-opacity.c
test_multistage_SOURCES           = test-multistage.c
test_pixmap_SOURCES               = test-pixmap.c
test_pixmap_LDFLAGS               = -lXcomposite
test_cogl_primitives_SOURCES      = test-cogl-primitives.c
test_cogl_tex_tile_SOURCES        = test-cogl-tex-tile.c
test_cogl_tex_convert_SOURCES     = test-cogl-tex-convert.c
test_cogl_tex_foreign_SOURCES     = test-cogl-tex-foreign.c
test_cogl_tex_getset_SOURCES      = test-cogl-tex-getset.c
test_cogl_offscreen_SOURCES       = test-cogl-offscreen.c
test_stage_read_pixels_SOURCES    = test-stage-read-pixels.c
test_random_text_SOURCES          = test-random-text.c
test_paint_wrapper_SOURCES        = test-paint-wrapper.c
test_texture_quality_SOURCES      = test-texture-quality.c
test_entry_auto_SOURCES	          = test-entry-auto.c
test_layout_SOURCES               = test-layout.c
test_invariants_SOURCES           = test-invariants.c
test_devices_SOURCES              = test-devices.c
test_label_cache_SOURCES          = test-label-cache.c
test_pick_SOURCES                 = test-pick.c

EXTRA_DIST = redhand.png test-script.json

endif
