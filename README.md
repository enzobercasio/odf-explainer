# OpenShift Data Foundation, Explained

An animated, single-page explainer for Red Hat OpenShift Data Foundation (ODF):

- **The life of a write:** follow block (RBD), file (CephFS) and object (MCG) requests from a pod down to three replicated disks.
- **The stack:** Ceph, Rook, Ceph-CSI, the Multicloud Object Gateway and the ODF operator.
- **Deployment modes:** Internal, Internal-attached, Compact, External, Stretch/arbiter and MCG only.
- **Requirements:** a sizing calculator, resource and platform tables, and a pre-flight checklist.

Figures come from the ODF 4.18 planning guide. Check the docs for your exact ODF version before planning a production deployment.

Open `index.html` in a browser; it has no build step.
