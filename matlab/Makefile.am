#
# Makefile.am for matlab files
#


foodir=$(prefix)/matlab/lme/geodesic
mfilesdir=$(prefix)/matlab
siemensdir=$(prefix)/matlab
lmefilesdir=$(prefix)/matlab/lme
lmegeofilesdir=$(prefix)/matlab/lme/geodesic
lmemassunifilesdir=$(prefix)/matlab/lme/mass_univariate
lmeunifilesdir=$(prefix)/matlab/lme/univariate
lmeQdecfilesdir=$(prefix)/matlab/lme/Qdec
samsegfilesdir=$(prefix)/matlab/samseg
survivalfilesdir=$(prefix)/matlab/Survival
survivalexdatafilesdir=$(prefix)/matlab/Survival/ex_data
survivalmassunifilesdir=$(prefix)/matlab/Survival/mass_univariate
survivalunifilesdir=$(prefix)/matlab/Survival/univariate

mfiles_DATA=\
	angles2rotmat.m \
	barsegstats.m \
	bmmcost.m \
	bmm_mcvect.m \
	bmm_mcvhist.m \
	bmmroc.m \
	cc_cut_afd.m \
	cc_cut_dir_afd.m \
	cc_cut_table.m \
	combine_labels.m \
	compute_opt_volume.m \
	convert_fieldsign.m \
	convert_unwarp_resample.m \
	cortical_labeling_afd_txt.m \
	cortical_labeling_dir_afd_txt.m \
	cortical_labeling_table.m \
	dice_labels.m \
	dilate3d.m \
	dtifa.m \
	dtimatrix.m \
	erode3d.m \
	fisher_twoclass.m \
	fread3.m \
	fwrite3.m \
	fs_ranksum.m \
	fs_signrank.m \
        fsgettmppath.m \
	irepierr.m \
	irepifit.m \
	irepifitvol.m \
	irepistructure.m \
	irepisynth.m \
	irepitiming.m \
	isdicomfile.m \
	juelichmat2mat.m \
	labelic.m \
	llbmm.m \
	load_analyze_hdr.m \
	load_analyze.m \
	load_cor.m \
	load_csd.m \
	load_dicom_fl.m \
	load_dicom_series.m \
	load_gca.m \
	load_ima.m \
	load_mgh2.m \
	load_mgh.m \
	load_nifti_hdr.m \
	load_nifti.m \
	load_segstats.m \
	lta_read.m \
	lta_write.m \
	mksubfov.m \
	mri_cdf2p.m \
	mri_glmfit_pcc.m \
	MRIeuler2Mdc.m \
	MRIextractImage.m \
	MRIfspec.m \
	MRIisBHDR.m \
	MRIisMGH.m \
	mri_kurtosis.m \
	MRImdc2euler.m \
	MRIread.m \
	MRIseg2labelxyz.m \
	MRIsegReg.m \
  mri_surfrft_jlbr.m \
	MRIvol2vol.m \
	MRIvote.m \
	MRIwrite.m \
	mri_zcdf.m \
	mris_display.m \
	peakfinder.m \
	pons_cut_afd.m \
	pons_cut_dir_afd.m \
	pons_cut_table.m \
	randb.m \
	read_all.m \
	read_annotation.m \
	read_ascii_curv.m \
	read_asc.m \
	read_cor.m \
	read_csf_patch.m \
	read_curv.m \
	read_eccen_patch.m \
	read_freq_patch.m \
	read_fscolorlut.m \
	read_genesis_image.m \
	read_label.m \
	read_label_old.m \
	read_moviebyu.m \
	read_patch.m \
	readrec.m \
	ReadSiemensPhysio.m\
	read_siemens_header.m \
	read_siemens_image.m \
	read_smooth_eccen.m \
	read_surf.m \
	read_type.m \
	read_vf.m \
	read_wfile.m \
	remove_spaces.m \
	ribbon_afd.m \
	ribbon_dir_afd.m \
	ribbon_table.m \
	rotmat.m \
	rotmat2angles.m \
	sampleSize.m \
	save_cor.m \
	save_mgh2.m \
	save_mgh.m \
	save_nifti.m \
	ssblochgrad.m \
	ssbloch.m \
	stringunique.m \
	strlen.m \
	subcortical_labeling_afd.m \
	subcortical_labeling_dir_afd.m \
	subcortical_labeling_table.m \
	surf_registration_afd.m \
	surf_registration_stats.m \
	surf_registration_table.m \
	talairaching_afd.m \
	talairaching_dir_afd.m \
	talairaching_stats.m \
	talairaching_table.m \
	unwarp_init_globals.m \
	unwarp_resample.m \
	unwarp_scanners_table.m \
	vox2ras_0to1.m \
	vox2ras_1to0.m \
	vox2ras_dfmeas.m \
	vox2ras_ksolve.m \
	vox2ras_rsolveAA.m \
	vox2ras_rsolve.m \
	vox2ras_tkreg.m \
	vox2rasToQform.m \
	wm_seg_afd.m \
	wm_seg_dir_afd.m \
	wm_seg_table.m \
	write_analyze_hdr.m \
	write_annotation.m \
	write_ascii_curv.m \
	write_curv.m \
	write_label.m \
	write_surf.m \
	write_wfile.m \
	xfm_read.m

if NMR_INSTALL
siemens_DATA=\
	read_meas_dat.m \
	read_meas_prot.m \
	read_meas_prot__struct.m
else
siemens_DATA=
endif

lmefiles_DATA=\
	lme/usage.txt \
	lme/fs_read_label.m \
	lme/fs_read_surf.m \
	lme/fs_read_Y.m \
	lme/fs_write_fstats.m \
	lme/fs_write_Y.m \
	lme/sortData.m

lmegeofiles_DATA=\
	lme/geodesic/geodesic_license.txt \
	lme/geodesic/geodesic_readme.txt \
	lme/geodesic/geodesic_matlab_api.h \
	lme/geodesic/create_flat_triangular_mesh.m \
	lme/geodesic/create_hedgehog_mesh.m \
	lme/geodesic/create_subdivision_pattern.m \
	lme/geodesic/example1.m \
	lme/geodesic/example2.m \
	lme/geodesic/example3.m \
	lme/geodesic/example4.m \
	lme/geodesic/example5.m \
	lme/geodesic/extract_coordinates_from_path.m \
	lme/geodesic/geodesic_convert_surface_points.m \
	lme/geodesic/geodesic_create_surface_point.m \
	lme/geodesic/geodesic_delete.m \
	lme/geodesic/geodesic_distance_and_source.m \
	lme/geodesic/geodesic_new_algorithm.m \
	lme/geodesic/geodesic_new_mesh.m \
	lme/geodesic/geodesic_propagate.m \
	lme/geodesic/geodesic_trace_back.m

lmemassunifiles_DATA=\
	lme/mass_univariate/AdjMtx.m \
	lme/mass_univariate/lme_FSfit.m \
	lme/mass_univariate/lme_mass_FDR2.m \
	lme/mass_univariate/lme_mass_FDR.m \
	lme/mass_univariate/lme_mass_fit_EMinit.m \
	lme/mass_univariate/lme_mass_fit_init.m \
	lme/mass_univariate/lme_mass_fit.m \
	lme/mass_univariate/lme_mass_fit_Rgw.m \
	lme/mass_univariate/lme_mass_fit_vw.m \
	lme/mass_univariate/lme_mass_F.m \
	lme/mass_univariate/lme_mass_LR.m \
	lme/mass_univariate/lme_mass_RgDist.m \
	lme/mass_univariate/lme_mass_RgEI1.m \
	lme/mass_univariate/lme_mass_RgEI.m \
	lme/mass_univariate/lme_mass_RgFSfit.m \
	lme/mass_univariate/lme_mass_RgGradient1.m \
	lme/mass_univariate/lme_mass_RgGradient.m \
	lme/mass_univariate/lme_mass_RgGrow.m \
	lme/mass_univariate/lme_mass_RgMean.m \
	lme/mass_univariate/lme_RgFSfit.m \
	lme/mass_univariate/parfor_progress.m \
	lme/mass_univariate/sphCoord.m

lmeunifiles_DATA=\
	lme/univariate/lme_EI.m \
	lme/univariate/lme_fit_EMinit.m \
	lme/univariate/lme_fit_EM.m \
	lme/univariate/lme_fit_FSinit.m \
	lme/univariate/lme_fit_FS.m \
	lme/univariate/lme_fit_init.m \
	lme/univariate/lme_fit_NR.m \
	lme/univariate/lme_F.m \
	lme/univariate/lme_Gradient.m \
	lme/univariate/lme_Hessian.m \
	lme/univariate/lme_lowessPlot.m \
	lme/univariate/lme_LR.m \
	lme/univariate/lme_plannedPower.m \
	lme/univariate/lme_plannedSampleSize.m \
	lme/univariate/lme_realizedPower.m \
	lme/univariate/lme_timePlot.m \
	lme/univariate/vec.m

lmeQdecfiles_DATA=\
	lme/Qdec/findQdecVar.m \
	lme/Qdec/fReadQdec.m \
	lme/Qdec/fWriteQdec.m \
	lme/Qdec/getQdecVarData.m \
	lme/Qdec/getQdecVars.m \
	lme/Qdec/num2Qdec.m \
	lme/Qdec/Qdec2num.m \
	lme/Qdec/rmQdecCol.m

samsegfiles_DATA=\
	samseg/run_samseg.m \
	samseg/samseg_coregisterAtlas_SPM.m \
	samseg/samsegment.m \
	samseg/samseg_registerToAtlas.m \
	samseg/samseg_writeOutFreeSurferSeg.m

samseg_binfiles=\
	samseg/samseg

survivalfiles_DATA=\
	Survival/SStat_lmeX_ext.m

survivalexdatafiles_datafiles=\
	Survival/ex_data/addicts.mat \
	Survival/ex_data/addicts.dat \
	Survival/ex_data/Qdec_addicts.dat \
	Survival/ex_data/vets.dat \
	Survival/ex_data/vets.mat

survivalmassunifiles_DATA=\
	Survival/mass_univariate/SStat_mass_FDR.m \
	Survival/mass_univariate/SStat_mass_FDR2.m \
	Survival/mass_univariate/SStat_mass_HR.m \
	Survival/mass_univariate/SStat_mass_CoxPH.m \
	Survival/mass_univariate/SStat_mass_PHTest.m \
	Survival/mass_univariate/parfor_progress.m \
	Survival/mass_univariate/SStat_mass_CoxExt.m \
	Survival/mass_univariate/SStat_mass_CoxStratPH.m

survivalunifiles_DATA=\
	Survival/univariate/SStat_PHTest.m \
	Survival/univariate/SStat_CoxExt.m \
	Survival/univariate/SStat_KM.m \
	Survival/univariate/SStat_CoxPH.m \
	Survival/univariate/SStat_X_ext.m \
	Survival/univariate/SStat_CoxStratPH.m \
	Survival/univariate/SStat_HR.m

foo_datafiles=lme/geodesic/geodesic_src.tar.gz

install-data-local:
	test -z $(DESTDIR)$(survivalexdatafilesdir) || $(mkdir_p) $(DESTDIR)$(survivalexdatafilesdir)
	$(INSTALL_DATA) $(survivalexdatafiles_datafiles) $(DESTDIR)$(survivalexdatafilesdir)
	test -z $(DESTDIR)$(foodir) || $(mkdir_p) $(DESTDIR)$(foodir)
	$(INSTALL_DATA) $(foo_datafiles) $(DESTDIR)$(foodir)
	test -z $(DESTDIR)$(bindir) || $(mkdir_p) $(DESTDIR)$(bindir)
	$(INSTALL_PROGRAM) $(samseg_binfiles) $(DESTDIR)$(bindir)


EXTRA_DIST=$(mfiles_DATA) \
	$(lmefiles_DATA) \
	$(lmegeofiles_DATA) \
	$(lmeunifiles_DATA) \
	$(lmemassunifiles_DATA) \
	$(lmeQdecfiles_DATA) \
	$(samsegfiles_DATA) \
	$(survivalfiles_DATA) \
	$(survivalexdatafiles_DATA) \
	$(survivalmassunifiles_DATA) \
	$(survivalunifiles_DATA)

# Our release target. Include files to be excluded here. They will be
# found and removed after 'make install' is run during the 'make
# release' target.
EXCLUDE_FILES=$(siemens_DATA)
include $(top_srcdir)/Makefile.extra
