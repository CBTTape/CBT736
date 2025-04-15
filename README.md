# CBT736
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 736 is from Mark Naughton of British Airways and contains *   FILE 736
//*           a Perl script to run under MVS Unix Services, which   *   FILE 736
//*           displays details about your IODF configuration.       *   FILE 736
//*                                                                 *   FILE 736
//*           The Perl script has DCB attributes of LRECL=420, so   *   FILE 736
//*           it has been sent here as an XMIT-format file, and it  *   FILE 736
//*           therefore must be RECEIVEd under TSO, as follows:     *   FILE 736
//*                                                                 *   FILE 736
//*             TSO RECEIVE INDS(this.dataset(IODF))                *   FILE 736
//*                                                                 *   FILE 736
//*           For further detail, see member $$NOTE1.               *   FILE 736
//*                                                                 *   FILE 736
//*           email:  mark.naughton@ba.com                          *   FILE 736
//*                                                                 *   FILE 736
//*     -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -     *   FILE 736
//*                                                                 *   FILE 736
//*     IODF.CGI Documentation                                      *   FILE 736
//*                                                                 *   FILE 736
//*     Introduction                                                *   FILE 736
//*                                                                 *   FILE 736
//*     This PERL script runs on the MVS Webserver and produces     *   FILE 736
//*     a table, in HTML, of channels, associated control units     *   FILE 736
//*     and devices. It also displays switch information.           *   FILE 736
//*                                                                 *   FILE 736
//*     It has been tested with IOCPs created for Amdahl and        *   FILE 736
//*     IBM z/Series machines running z/OS 1.4.                     *   FILE 736
//*                                                                 *   FILE 736
//*     Configuration                                               *   FILE 736
//*                                                                 *   FILE 736
//*     1.  Update the 1st line of the script to point to your      *   FILE 736
//*         PERL interpreter.                                       *   FILE 736
//*                                                                 *   FILE 736
//*     2.  Copy the script into a directory - making sure you      *   FILE 736
//*         update the cgi_directory variable above. Make sure      *   FILE 736
//*         the script is named iodf.cgi.                           *   FILE 736
//*                                                                 *   FILE 736
//*     3.  Copy the IOCPs/IODFs (as text files) into the           *   FILE 736
//*         directory you have specified in data_directory. We      *   FILE 736
//*         use the naming convention of IODFxx.PROC where xx       *   FILE 736
//*         is the two digit ID of the IODF.                        *   FILE 736
//*                                                                 *   FILE 736
//*     3.1 There is a sample JCL step at the bottom of this        *   FILE 736
//*         file which we use to copy the production IODF/IOCPs     *   FILE 736
//*         into our USS directories.                               *   FILE 736
//*                                                                 *   FILE 736
//*     4.  Update the title variable in the script.                *   FILE 736
//*                                                                 *   FILE 736
//*     5.  Update the device_sw_list to display CU types for       *   FILE 736
//*         certain IODEVICE unit types in the Switch display.      *   FILE 736
//*                                                                 *   FILE 736
//*     6.  Then try it through your browser! Currently the         *   FILE 736
//*         Cascading Style Sheet uses IE-specific options.         *   FILE 736
//*                                                                 *   FILE 736
```
