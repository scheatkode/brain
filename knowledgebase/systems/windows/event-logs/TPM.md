# TPM

<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Name</th><th>Id</th><th>Description</th></tr>
<tr><td>TPM</td><td>2</td><td>The TPM self test command failed.</td></tr>
<tr><td>TPM</td><td>12</td><td>The device driver for the Trusted Platform Module (TPM) encountered an error in the TPM hardware, which might prevent some applications using TPM services from operating correctly.  Please restart your computer to reset the TPM hardware.  For further assistance on this hardware issue, please contact the computer manufacturer for more information.</td></tr>
<tr><td>TPM</td><td>14</td><td>The device driver for the Trusted Platform Module (TPM) encountered a non-recoverable error in the TPM hardware, which prevents TPM services (such as data encryption) from being used. For further help, please contact the computer manufacturer.</td></tr>
<tr><td>TPM</td><td>15</td><td>The device driver for the Trusted Platform Module (TPM) encountered a non-recoverable error in the TPM hardware, which prevents TPM services (such as data encryption) from being used. For further help, please contact the computer manufacturer.</td></tr>
<tr><td>TPM</td><td>16</td><td>A compatible TPM is not found.</td></tr>
<tr><td>TPM</td><td>17</td><td>The Trusted Platform Module (TPM) hardware failed to execute a TPM command.</td></tr>
<tr><td>TPM</td><td>18</td><td>This event triggers the Trusted Platform Module (TPM) provisioning/status check to run.</td></tr>
<tr><td>TPM</td><td>19</td><td>The system firmware failed to enable overwriting of system memory on restart. The ACPI request could not be interpreted by the firmware. The firmware should be upgraded.</td></tr>
<tr><td>TPM</td><td>20</td><td>A command was sent to the Trusted Platform Module (TPM) successfully resetting the TPM lockout logic. This event is generated when a successful command sent to the TPM resets the TPM lockout logic.  With this event, all prior standard user TPM authorization failures are ignored; allowing standard users to use the TPM normally again immediately.</td></tr>
<tr><td>TPM</td><td>21</td><td>A standard user issued Trusted Platform Module (TPM) command returned an authorization failure. This event is generated when a command sent to the TPM by a standard user returns a response indicating an authorization failure.  If too many authorization failures occur, standard users may be temporarily prevented from sending TPM commands requiring authorization.  This helps prevent the TPM from entering a hardware lockout because of too many authorization failures. 
User Security ID:%1. 
Process Path %2.</td></tr>
<tr><td>TPM</td><td>22</td><td>TPM Base Services (TBS) has been configured in a test mode until the next full restart. The TBS will not perform TPM resource virtualization or TPM command blocking until the next full restart.</td></tr>
<tr><td>TPM</td><td>23</td><td>A standard user Trusted Platform Module (TPM) command was blocked because the standard user has exceeded the maximum authorization failures permitted. This event is generated when too many recent TPM commands sent to the TPM by a standard user returned a response indicating an authorization failure.  The standard user is currently temporarily prevented from sending TPM commands requiring authorization.  This helps prevent the TPM from entering a hardware lockout because of too many authorization failures. 
User Security ID:%1.</td></tr>
<tr><td>TPM</td><td>24</td><td>The Trusted Platform Module (TPM) status: %1 and %2.</td></tr>
<tr><td>TPM</td><td>25</td><td>Creation of the Windows AIK directory failed.</td></tr>
<tr><td>TPM</td><td>26</td><td>Creation of provisioning event has failed.</td></tr>
<tr><td>TPM</td><td>27</td><td>The initialization of the Trusted Platform Module (TPM) failed. The TPM may be in failure mode. To allow diagnosis, contact the TPM manufacturer with the attached information.</td></tr>
</table>
