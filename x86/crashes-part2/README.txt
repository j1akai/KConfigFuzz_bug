New crashes found in kconfigfuzz that are not in crashes-part1
================================================================================

Total new crashes: 29


Kernel 6.16: 4 crashes
----------------------------------------
1. WARNING in call_timer_fn
   Description: WARNING in call_timer_fn

2. kernel BUG in assfail
   Description: kernel BUG in assfail

3. WARNING locking bug in ocfs2_inode_lock_full_nested
   Description: WARNING: locking bug in ocfs2_inode_lock_full_nested

4. INFO task hung in gfs2_jhead_process_page
   Description: INFO: task hung in gfs2_jhead_process_page


Kernel 6.2: 5 crashes
----------------------------------------
1. WARNING ODEBUG bug in netdev_run_todo
   Description: WARNING ODEBUG bug in netdev_run_todo

2. BUG sleeping function called from invalid context in console_lock
   Description: BUG: sleeping function called from invalid context in console_lock

3. WARNING in io_ring_exit_work
   Description: WARNING in io_ring_exit_work

4. WARNING in _copy_from_iter
   Description: WARNING in _copy_from_iter

5. INFO task hung in gfs2_jhead_process_page
   Description: INFO: task hung in gfs2_jhead_process_page


Kernel 6.8: 20 crashes
----------------------------------------
1. BUG unable to handle kernel NULL pointer dereference in reset_interrupt
   Description: BUG: unable to handle kernel NULL pointer dereference in reset_interrupt

2. BUG unable to handle kernel paging request in neigh_flush_dev
   Description: BUG: unable to handle kernel paging request in neigh_flush_dev

3. WARNING in folio_account_dirtied
   Description: WARNING in folio_account_dirtied

4. BUG sleeping function called from invalid context in console_lock
   Description: BUG: sleeping function called from invalid context in console_lock

5. INFO task hung in nci_stop_poll
   Description: INFO task hung in nci_stop_poll

6. BUG MAX_LOCKDEP_KEYS too low!
   Description: BUG MAX_LOCKDEP_KEYS too low!

7. INFO task hung in rfkill_global_led_trigger_worker
   Description: INFO task hung in rfkill_global_led_trigger_worker

8. INFO task hung in nci_close_device
   Description: INFO task hung in nci_close_device

9. possible deadlock in ntfs_read_block
   Description: possible deadlock in ntfs_read_block

10. INFO task hung in sync_bdevs
   Description: INFO task hung in sync_bdevs

11. BUG unable to handle kernel paging request in debug_check_no_obj_freed
   Description: BUG: unable to handle kernel paging request in debug_check_no_obj_freed

12. WARNING in fw_load_sysfs_fallback
   Description: WARNING in fw_load_sysfs_fallback

13. INFO task hung in nfc_targets_found
   Description: INFO task hung in nfc_targets_found

14. INFO task hung in nbd_queue_rq
   Description: INFO task hung in nbd_queue_rq

15. WARNING locking bug in nci_close_device
   Description: WARNING: locking bug in nci_close_device

16. WARNING task hung in rfkill_unregister
   Description: INFO: task hung in rfkill_unregister

17. INFO task hung in nfc_rfkill_set_block
   Description: INFO: task hung in nfc_rfkill_set_block

18. INFO task hung in nfc_urelease_event_work
   Description: INFO task hung in nfc_urelease_event_work

19. kernel BUG in ntfs_file_write_iter
   Description: kernel BUG in ntfs_file_write_iter

20. INFO task hung in migrate_folio_unmap
   Description: INFO: task hung in migrate_folio_unmap

