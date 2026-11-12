# Troubleshooting Log

Recorded October 29, 2026. Exact hands-on test times were not recorded.

1. **Client report:** Printer would not power on; previous printing problems led the client to buy another printer.
2. **Power test (reported by project owner):** Changing the power cord allowed the printer to power on. Original cord/connection suspected; internal power-supply failure not established.
3. **Error documented:** “Ink Cartridge is not installed correctly,” with BK indicated.
4. **Initial working hypothesis:** Black cartridge might not be fully seated. Reseating was suggested but was not reported as performed.
5. **Visual inspection:** Empty BK slot confirmed in IMG_1100.HEIC. This supersedes the initial assumption that a black cartridge was present but loose.
6. **Other visible observations:** M/Y/C cartridges present; no obvious jam or broken part visible. Photo cannot verify ink levels, electrical contacts, nozzle condition, or printhead operation.
7. **Pause point:** No black cartridge installed and no successful print documented. Resume with compatible cartridge installation and functional testing.

## Evidence inventory
- IMG_1099.HEIC → 01-printer-model.jpg
- IMG_1096.HEIC → 02-black-cartridge-error.jpg
- IMG_1100.HEIC → 03-missing-black-cartridge.jpg
- Earlier supplied files: IMG_1088–IMG_1094.HEIC and IMG_1095.MOV. These were not reliably reviewed during the initial discussion and are not used here to support additional findings.

## Next entry template
**Date:**  
**Action:**  
**Observed result:**  
**Evidence file:**  
**Next step:**

## November 12, 2026 — Project resumed
Cartridges replaced and installation errors cleared per owner. An 802XL black cartridge is visible. Print testing produced a Printing screen and new Printer Error 000084; a separate prompt recommends a nozzle check. No successful output confirmed. [Evidence inventory and next tests](updates/2026-11-12.md).

## November 12 follow-up — Blank page, cleaning, partial output
- Owner reported a blank sheet from the printer's built-in nozzle check.
- IMG_1264 and IMG_1265 show cleaning in progress; they do not establish the number of separate cycles.
- IMG_1266 shows the screen asking the operator to compare the printed result. This is not an automatic pass.
- IMG_1267 and IMG_1268 show visible line blocks with gaps/missing sections. Complete output across all ink channels cannot be established from the photos.
- Progress: output is no longer entirely blank. Repair remains incomplete; recurrence of 000084 is unknown.
- Next: if no active error and fewer than four cleanings have been run in this session, run one guided cleaning and a fresh nozzle check. Keep each page separate and record the cycle count. If no improvement after up to four cleanings, Epson specifies at least six hours without printing before retrying; persistent poor output warrants Epson support. Do not interrupt cleaning.
- Reference: [Epson user guide, printed pages 240–243 and 247](https://files.support.epson.com/docid/cpd5/cpd53013.pdf).

### Cleaning count confirmed by owner
The owner confirmed three cleaning cycles were performed before ink first appeared on the page. This replaces the previously unknown cycle count. Visible ink output improved from blank to partial patterns; full print quality remains unverified. Recurrence of 000084 has not been confirmed.

### Error recurrence check
The owner confirmed error 000084 has not returned during the recent tests. This supersedes the earlier unknown recurrence status; it does not establish permanent resolution. Current remaining symptom is incomplete nozzle-check output after three cleaning cycles.

### Follow-up photo IMG_1271.HEIC
The new page shows two visible line blocks; the right block appears more continuous while the left retains faint/broken sections. Full output across all four ink channels is not evident, so the nozzle check is not recorded as passed. The image followed advice to perform a fourth cleaning, but completion of that fourth cycle has not been explicitly confirmed. Next: if four cycles have been completed, stop cleaning and allow at least six hours without printing before a fresh nozzle check. Prior report: 000084 had not returned.

### Correction based on IMG_1272.HEIC and owner inspection
Both visible line blocks show continuous lines in the clearer photo. The earlier interpretation of faint/broken sections in IMG_1271 is withdrawn; that image did not justify recommending additional cleaning. Do not record this as confirmed failure of the left block. Next: accept the no-gaps option for these displayed patterns and test a short black-text document and a small color sample. All four ink channels and overall document quality remain unverified. Cleaning count beyond the three confirmed cycles remains unconfirmed.

### Error recurrence during phone printing
Owner reports the same previously documented error (000084) returned during an image print from a phone. Paper began feeding and the pending job produced a blank page. This supersedes the earlier report of no recurrence. Both visible blocks in the preceding local test had continuous lines, but that did not validate all ink channels or a complete repair. Next isolation test: cancel the phone job, restart normally, then run a fresh control-panel nozzle check and a standalone copy. Record output and whether the error returns before changing phone/network settings or running further cleaning.

### Restart popup — IMG_1273.HEIC
After restart the owner photographed an Information message recommending a Print Head Nozzle Check because the printhead may require maintenance. This photo does not show 000084 and does not establish a failed printhead. The previously recurring 000084 remains unresolved. Next: dismiss the advisory and, if no blocking error is present, perform the planned standalone copy; record whether it produces readable output, a blank page, or an error. Further cleaning is not justified by this advisory alone.

### Standalone copy test — blank output
Owner placed a page on the scanner glass and reports blank copies. This reproduces blank output independently of the phone print path, but does not yet distinguish scan capture from ink/print output. Original placement, whether it contained visible print, copy color mode, scan preview, and error recurrence during this test remain unconfirmed. Next: confirm a printed original is face down at the alignment mark, then inspect a scan preview or saved scan without printing. If the scan contains the original but copies remain blank, investigate print/ink output; if the scan is blank, investigate placement/scanning. Earlier two continuous line blocks do not establish all four ink channels work. Avoid further cleaning until these checks clarify the failure.

### Copy modes and scan preview confirmed — IMG_1274–IMG_1276
Owner reports trying both color and black-and-white copy modes in the continuing blank-copy investigation. Photos confirm both mode selections. IMG_1274 shows a nonblank document captured in the copy preview, so original placement and scan capture worked for this test. Blank output is therefore downstream of image capture; the phone/network is not required to reproduce it. A specific printhead, ink-supply, or electronics failure remains unconfirmed. The two continuous blocks previously photographed did not validate every ink channel. Next: obtain one fresh complete control-panel nozzle-check page, including all expected color/black patterns, without another cleaning first; compare against the WF-4730 reference. Record whether 000084 recurs during the copy or nozzle test. Do not publish the document-preview photo without redacting its contents.

### Latest test-page photo — IMG_1277.HEIC
Photo again shows two continuous blue/cyan-looking line blocks. Distinct black, magenta, and yellow output is not visible in the photographed area; lighting and test type must be considered before assigning missing channels. This is not a confirmed complete four-color nozzle-check pass. Next: confirm the page was produced specifically by Maintenance > Print Head Nozzle Check (rather than alignment), inspect the sheet in daylight for faint yellow/other patterns, and check displayed ink levels. No further cleaning or parts purchase recommended solely from this photo. If the correct test repeatedly produces only these blocks and standalone copies remain blank despite a nonblank preview, escalate with these results and recurring 000084 to Epson rather than claiming a specific failed component.

### Test type and visible color confirmed by owner
Owner confirms IMG_1277 was produced by Maintenance > Print Head Nozzle Check and both visible blocks are blue. No other colored patterns were reported. The full nozzle check is therefore not a pass, even though the two visible blocks have continuous lines. Black/magenta/yellow output is not demonstrated; a specific clogged channel or failed part is not diagnosed. Combined evidence: nonblank scan preview, blank copies in both modes, blank phone print, and recurrence of 000084. Next checks: displayed ink levels and correct cartridge preparation/installation per Epson, with no automatic recommendation to buy parts. After the advised rest if four cleanings were performed, retry once; persistent missing output or recurring 000084 warrants Epson service assessment.
