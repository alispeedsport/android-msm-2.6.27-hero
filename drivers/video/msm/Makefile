
# core framebuffer
#
obj-y := msm_fb.o logo.o
ifeq ($(CONFIG_FB_MSM_LOGO),y)
obj-y += logo.o
endif

# MDP DMA/PPP engine
#
obj-y += mdp.o mdp_scale_tables.o mdp_ppp.o

# MDDI interface
#
obj-y += mddi.o

# MDDI client/panel drivers
#
obj-y += mddi_client_dummy.o
obj-y += mddi_client_toshiba.o
obj-y += mddi_client_eid.o mddi_eid_cabc.o
obj-y += mddi_client_eid0154.o
obj-y += mddi_client_nt35399.o
